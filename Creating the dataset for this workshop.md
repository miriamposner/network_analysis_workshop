This workshop is designed to be used in a classroom with 20 or more students. You'll use students' preferences to show them how they're connected with each other (and who should be friends with whom!). Rather than using an existing dataset, the students will create the dataset themselves by answering a few questions about their preferences.  

To do this, have them fill out a form with four (or so) questions. Each question should have five (or so) options. I used Google Forms; you can use whatever you want. The questions I used were:  

* What is your favorite band? (Options were the first five bands I could think of)
* What is your favorite book? (Again, the first five options I could think of)
* What is you favorite food? (Ditto)
* What is your favorite thing to do when you have free time? (Ditto)

Once you have the spreadsheet containing their answers, turn it into an edge list. The source should be students; the target should be preferences. I use OpenRefine's [transpose function](http://googlerefine.blogspot.com/2011/09/json-code-to-transpose-important-number.html) to do this. You should also create a node list that contains a node-type column that classifies nodes as either "student" or "preference." 

If you want to show students the difference between a two-mode and a one-mode network, you can use [these instructions](http://electricarchaeology.ca/2012/04/04/converting-2-mode-with-multimodal-plugin-for-gephi/) from Shawn Graham to project your two-mode edge list into a one-mode edge list. 
