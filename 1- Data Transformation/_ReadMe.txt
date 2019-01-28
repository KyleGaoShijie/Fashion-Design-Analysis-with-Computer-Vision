############## Brief Description of the Codes ##################


## 1. Cleaning class names (chinese)

Code to gather the Object names that are in Chinese and select the proper deliminter (which could be Chinese characters as well) to segegrate objects and have each of them in a single column.
This will help in creating a transation and create a mapping file between Chinese and English objects

## 2. Segregate Images based on labels

Creating a new format of folder structure where each image would be under its corresponding label name.

For example,

train
	-- label 0
		-- img 1
		-- img 2
		..
		..
	-- label 1
		-- img 10
		-- img 11

test
	-- label 0
		-- img x1
		-- img x2
		..
		..
	-- label 1
		-- img x3
		-- img x4
		
		
## 3. Transforming the input images

	* Converting all the images to a common size maintaining the same aspect ratio
	* The extra spaces are filled with the majority of the color found using the histogram
	* Creating a Train and Test file separately
	
	
		
		
	
