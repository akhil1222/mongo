# mongo

# create a database by using the following command
   >use SACHINTENDULKAR
    
# now create a collection 
   >db.createCollection("Twitter")

# now storing each tweet of sachin in this collecton
Inserting tweet 1:

   >db.Twitter.insert({
   tweet: "Introducing Truebluebrand to the world was an amazing experience! A truly global fashion brand with an Indian soul.",
   date: "july 1,2016",
   likes: 2600
   })
  
Inserting tweet 2:
   >db.Twitter.insert({
   tweet: "Enjoyed the Castles in Scotland",
   date: "july 1,2016",
   likes: 6900
   })
  
Inserting tweet 3:
   >db.Twitter.insert({
   tweet: "The solitude and remote stretches in Scotland",
   date: "july 2,2016",
   likes: 7400
   })
  
Inserting tweet 4:
   >db.Twitter.insert({
   tweet: "Happy birthday Bhajji! May God bless you with good health and happiness. Have a great year buddy!",
   date: "july 3,2016",
   likes: 13000
   })
   
Inserting tweet 5:
   >db.Twitter.insert({
   tweet: "Ring mein ghusne k baad darr nahi lagta chahe harun ya jeetun",
   date: "july 3,2016",
   likes: 2300
   })
   
Inserting tweet 6:
   >db.Twitter.insert({
   tweet: "Some injuries trouble even after retirement, Will be back soon doing things I enjoy. Had a knee operation & resting.",
   date: "july 6,2016",
   likes: 8700
   })
   
Inserting tweet 7:
   >db.Twitter.insert({
   tweet: "Andar se feel hona chahiye ki kuch karna hai.",
   date: "july 6,2016",
   likes: 2000
   })
   
Inserting tweet 8:
   >db.Twitter.insert({
   tweet: "Watched you fight back from 2 sets down and 0-40 down on your serve. Great fight back and fantastic spirit. All the best!",
   date: "july 6,2016",
   likes: 8900
   })
   
Inserting tweet 9:
   >db.Twitter.insert({
   tweet: "Eid Mubarak!!",
   date: "july 6,2016",
   likes: 4100
   })
   
Inserting tweet 10:
   >db.Twitter.insert({
   tweet: "Happy Birthday @msdhoni .. Have a wonderful and blessed year ahead!!",
   date: "july 7,2016",
   likes: 10000
   })
   
Inserting tweet 11:
   >db.Twitter.insert({
   tweet: “Its one chance & you have to do what you've got with this..",
   date: "july 7,2016",
   likes: 2200
   })
   
Inserting tweet 12:
   >db.Twitter.insert({
   tweet: "Happy Birthday Dada, May all your dreams come true!!",
   date: "july 8,2016",
   likes: 9600
   })
   
Inserting tweet 13:
   >db.Twitter.insert({
   tweet: "Well done Capt. R Menon, first woman recipient of Exceptional Bravery at Sea, International Maritime Organisation for saving fishermen lives",
   date: "july 9,2016",
   likes: 2400
   })
   
# All the tweets were stored in the collection "Twitter" of "SACHINTENDULKAR" database.
# To see the collection use the following command
  >db.Twitter.find()
   
