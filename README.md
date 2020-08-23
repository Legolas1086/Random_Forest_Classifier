# Random_Forest_Classifier
Random forest classifier on simple data:

         This algorithm creates n decision trees where n will be given as a 
      parameter while creating object of this algo class. The train data will be 
      split among these decision trees randomly.Each Tree will be slightly different
      as they are built on different values.
        Now during prediction new independent varialbles are fed into all the
      decision trees and the predicton of all the trees are checked.
      The category or class having highest vote from the trees is selected as 
      answer
