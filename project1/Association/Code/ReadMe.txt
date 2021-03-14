Required Packages to run the file
1. itertools

Run the code
1. The code is written in python jupyter notebook
2. First, Click on the first cell and run it by using clicking run command in the above or using 'Shift + Enter'.
2. Second cell in the notebook is the starting point of the execution.
3. To run the first part of the part2 i.e to generate the number of frequent sets given support and confidence,
    input the values of support and confidence variables.
    example : support = 50
              confidence = 70
    output : Number of length 1 frequent itemsets 109
            Number of length 2 frequent itemsets 63
            Number of length 3 frequent itemsets 2
            Total Frequent Itemset Generated for Support 50 and Confidence 70 : 174
4. Then click on the second cell and run it by using clicking run command in the above or using 'Shift + Enter'.
5. Output of the first part will be generated i.e., gives the number of all frequent itemsets.
6. Prior to running the second part, run the first cell and second cell again.
7. For second part of part2, give the queries in separate cells of notebook and run the cell usng 'Shift + Enter'.
8. Give the queries for each template as follows:
  Template1 -
    example1 : (result11, cnt) = asso_rule.Temp_1("RULE", "ANY", ['G59_Up'])
    example2 : (result19, cnt) = asso_rule.Temp_1("BODY", 1, ['G59_Up', 'G10_Down'])
  Template2 -
    example1 : (result22, cnt) = asso_rule.Temp_2("HEAD", 2)
    example2 : (result23, cnt) = asso_rule.Temp_2("BODY", 1)
  Template3 -
    example1 : (result31, cnt) = asso_rule.Temp_3("1or1", "HEAD", "ANY", ['G10_Down'], "BODY", 1, ['G59_UP'])
    example2 : (result32, cnt) = asso_rule.Temp_3("1and1", "HEAD", "ANY", ['G10_Down'], "BODY", 1, ['G59_Up'])
    example3 : (result34, cnt) = asso_rule.Temp_3("1and2", "HEAD", "ANY", ['G10_Down'], "BODY", 2)
9. Check the output of cnt after running the cell containing query.


References :
http://www.vucreations.com/articles/apriori-algorithm-from-scratch-Python.html
https://analyticsindiamag.com/beginners-guide-to-understanding-apriori-algorithm-with-implementation-in-python/
