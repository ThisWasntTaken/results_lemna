pdf refers to the PDF Malware dataset
pdf_bin is the binarized version of the PDF Malware dataset

both datasets were split with train_test_split with 20% for test data

pdf_test_compare uses the test pdf data in both dmm.r and Analysis.r
pdf_train_compare uses the train pdf data in dmm.r and the test pdf data in Analysis.r
pdf_bin_train_compare uses the train pdf_bin data in dmm.r and the test pdf_bin data in Analysis.r

The TT variable in dmm.r is set to 2000, it was originally 20000. However, this does not make any difference.