# pretrained_dog_classifier_python
This is part of my Udacity AI Programming Nanodegree program. Using pretrained dog classifiers to classify dog breeds


# Objectives
-Correctly identify which pet images are of dogs (even if breed is misclassified) and which pet images aren't of dogs.
-Correctly classify the breed of dog, for the images that are of dogs.
-Determine which CNN model architecture (ResNet, AlexNet, or VGG16), "best" achieve the objectives 1 and 2.
-Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms take to run.

# Project Specififcations
-calls the time functions before the start of main code and after the main logic has been finished.
-adds command line argument for '--dir': uses default ='pet_images/'
-adds command line argument for '--arch': default='vgg'
-adds command line argument for '--dogfile': default='dognames.txt'
-makes sure files starting with '.' are ignored: checks for '.' using a conditional statement.
-dictionary key and label are in the correct format and retrieves 40 key-value pairs. e.g:- {'Poodle_07956.jpg': ['poodle'], 'fox_squirrel_01.jpg': ['fox squirrel'] ... }
'in_arg.dir' is passed as an argument inside check_images.py while calling the get_pet_labels function.
appends images_dir to each value before making the function call.
-classifier(images_dir+users_key, model)
-convert the output to lower case and strip any whitespaces
-appends 1 to correct label, and 0 to falsely classified values, classifying Labels as dogs
-check the displayed output and see if all matches are appropriately displayed.
-check the displayed output and see if all non matches are appropriately displayed Results
-all three models score as expected

