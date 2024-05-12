################################################################
#The external dynamic list can include individual IP addresses, subnet addresses (address/mask), or range of IP addresses. In addition, the block list can include comments and special characters such as * , : , ; , #, or /. The syntax for each line in the list is [IP address, IP/Mask, or IP start range-IP end range] [space] [comment].
#Enter each IP address/range/subnet in a new line; URLs or domains are not supported in this list. A subnet or an IP address range, such as 92.168.20.0/24 or 192.168.20.40-192.168.20.50, count as one IP address entry and not as multiple IP addresses. If you add comments, the comment must be on the same line as the IP address/range/subnet. The space at the end of the IP address is the delimiter that separates a comment from the IP address.
#An example IP address list:
#192.168.20.10/32 
#	2001:db8:123:1::1 #test IPv6 address 
#	192.168.20.0/24 ; test internal subnet 
#	2001:db8:123:1::/64 test internal IPv6 range 
#	192.168.20.40-192.168.20.50
# :\\\DoNotUSE the address 0.0.0.0/0 ////:
# :\\\DoNotUSE the address 192.168.0.0/16 ////:
# :\\\DoNotUSE the address 10.0.0.0/8 ////:
# :\\\DoNotUSE the address 172.16.0.0/12 ////:
################################################################



#NOC-IP-LIST
