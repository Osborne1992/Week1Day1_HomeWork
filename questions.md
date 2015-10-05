  1. Assign to the value `6` to the variable `number_six` - number_six = 6
  2. What is the datatype of `"Matz"`? - It is a String.
  3. What do the following expressions evaluate to:
    * `"Cool" + "Cool" + "Cool"` - "CoolCoolCool"
    * `t = "Troy"
      a = "Abed"
      "#{t} and #{a} in the Morning"` - "Troy Abed in the Morning"
    * `10 * 3` - 10 times by 3 = 30
    * `10 ** 3` - 10 to the power of 3 = 1000
    * `10 % 3` - What is the remainder of how many times 3 can go into 10. 3 remainder 1. 
    * `10 / 3` - What is 10 divided by 3. 3.
    * `0.7 + 0.1` - 0.7999999999999999 "floating point error"
  4. Can you explain why the expressions all give the same result?
    * `"Ronnie " + "Pickering"`
    * `"Ronnie ".+("Pickering")`
    * `"Ronnie ".send(:+, "Pickering")' - They are all different methods of saying the same thing.
  5. Please fix the following buggy expressions:
    * `number six = 6` - number_six = six
    * `"Maroon" + 5` - '"Maroon" + 5.to_s'
    * `ture == flase` - 'true == false' - Was the typo the actual error here? I am unsure.