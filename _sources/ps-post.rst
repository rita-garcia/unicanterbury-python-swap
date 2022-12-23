Post Test
-----------------------------------------------------

Please answer
the following problems to the best of your ability without any
outside help. You can stop working on a problem after you worked
on it for about five minutes without solving it.

Problems
==============

.. activecode:: ps-swap-ac
   :autograde: unittest

   Finish writing the code to swap the values in a and b (so that a ends up with b's initial value and b ends up with a's initial value).
   ~~~~

   x = 6
   y = 2
   temp = 0

   // swap the values

   // print the values
   print(x)
   print(y)
   ====
   from unittest.gui import TestCaseGui
   class myTests(TestCaseGui):

       def testOne(self):
           self.assertAlmostEqual(x, 2, "value of x after swap")
           self.assertAlmostEqual(y, 6, "value of x after swap")

   myTests().main()


Feedback
==================================

.. shortanswer:: ps-posttest-sa

   Please provide feedback here. Please share any comments, problems, or suggestions.

Thank You
============================
Thank you for taking part in this study!  We appreciate your time on this.
