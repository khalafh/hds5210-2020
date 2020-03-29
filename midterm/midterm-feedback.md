# Midterm Feedback

## Overall Score: 
47 / 50

Generally, you had all the right ideas. When it came to the work of reading the file off of the internet and comparing against known scores, there's more that could be done there.  Finally, remember to look for patterns in the code you're writing and consider a way to make that code more generic rather than duplicating it.  Nice work!


## Part 1: Creating a JSON Rules File
Comments - Nice work.  They all look great.

## Part 2: Functions to evaluate rules
Comments - These all look great in general.  The one thing you miight notice, though, is that you're writing a lot of the kind of code over and over -- the range comparison.  When I suggested that you should be able to do this without writing quite as much code, I was suggesting that you could write a generic function that would do any range lookup given the configuration file, the value, and which section to look in.  (-1)

Your FiO2 section used the FiO2 ranges niicely, but then had to hardcode getting either the 'Pa02' or 'A-a gradient' value sets.  If you had restructured your JSON slightly, then this wouldn't have needed to have that informaiton either.  (-1)

With accute / chronic renal failure, this could have been simplified with config.get(Renal_Failure) instead o fputting that condition in there.  No points off on this one, though.

## Part 3: Put it all together
Comments - Nice and simple.

## Part 4: Accessing and processing the patient file
Comments - One part of the intent I had was for you to have Python code download the files for you.  That's OK, though.

You also didn't complete the work of actually demonstrating the comparison part of the assignment.  (-1)
