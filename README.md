# CS300-P07
## This is the programming assignment at UW-Madison (PO7 Hyperloop)

- LoopStation class is CORRECTLY implemented
- Track class has TWO methods not passing the GradeScope Autograder:
  ``` -1.0: Verifies that findPassenger() correctly finds a passenger in the only Pod in the track.
org.opentest4j.AssertionFailedError: Called findPassenger() with a passenger in the only Pod on the track, but your method did not return the correct index. ==> expected: <0> but was: <-1>
-1.0: Verifies that addPassenger() correctly adds a passenger to the only Pod in the track.
org.opentest4j.AssertionFailedError: Called addPassenger() with a passenger whose isFirstClass matched the only (empty) pod on the Track ==> expected: <true> but was: <false> ```
