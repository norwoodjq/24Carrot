# 24Carrot
Urban gardening loyalty program

User checks in with NFC tag or a smart phone, user is geolocated 
If user is trusted user or if checking in with trusted authority
  if user geolocation matches the correct values
    if user can afford to post the bond, 100 units (worth equivalent of $10)
      a bond is placed in escrow - escrow period is 8 hr
      escrow receives 1000 units from community address
If escrow expires without fullfillment, bond moves to community address
If user checks out before escrow expires, bond moves to user
   user earns 100 units * elapsed time (hours) (800 units max)
     earnings move from escrow to user address
     800 - earning moves from escrow to community address
     200 units reserved for transaction fees
     transaction fees paid to miners
     balance 200-transcaction fees is moved to community address
 trusted user account balance must be > 10,000
 trusted authority account balance must be > 100,000
 
 genesis block transactions
 initial community address is granted 23,000,000 units
 five trusted authority addresses are granted 200,000 units each
