# COSC 111 Final Exam


Complete any FIVE for full points in the final. Each is worth 20 points.

Any additional you complete is extra credit and worth 10 points.

Fix the following unit tests.

  1. **Test1ConverterTest**: Fix the unit test so that the function Converter converts miles to kilometers or kilometers to miles depending on the second parameter mode. If mode is 1, it converts kilometers to miles and if mode is 2, it converts miles to kilometers.
  
  1. **Test2GenerateRandoms**: Fix the test so that we can generate an array of random numbers. The size of the array and the min and max of the values that can be generated are given.

  1. **est3FinndSmallestFactor**: Fix the unit test so that we are able to find the smallest number that divides two numbers. For example, 5 is the smallest number that divides both 10 and 15.

  1. **Test4FindMean**: The mean of an array is defined as the sum of the array divided the size of the array. For example, if the array is [1,2,3], the sum is 6 and size is 3. So, the mean of the array is 6/3=2. Fix the unit test to calculate the mean of an array.

  1. **Test5IsMISSN**: The first three digits of the Social Security Number are called the area number which is determined by the geographical region. If the social security number was issued in Michigan, it would between 362 and 386. Fix the test that determines if the social security number was issued in Michigan.
  *HINT*: If you have the number 12345 and want the first digit, 12345/100 = 123 since integers do not have a decimal places.

  1. **Test6CalculateDoublingTime**: The doubling time is the time for a loan to double. For example, a student loan taken at 5% APR will double in 14.2 years and a credit card loan at 29.99% will double in 2.64 years. The formula for the doubling time is given in https://en.wikipedia.org/wiki/Doubling_time Fix the unit test that calculates the doubling time.
  *HINT*: Use at the Math package for mathematical formulas.

  1. **Test7NetworkMACAddress**: Each network interface is assigned a unique number during manufacturing called the MAC address. When connecting to your wifi, your device broadcasts its MAC address. Fix the unit test such that the NetworkInterface class stores the MAC address in a member variable and is able to compare if it equal to a given MAC address string.

  1. **Test8AddressFormat**: Fix the unit test such that the Address object toString method returns a a properly formatted address. Be sure to override the toString method.

  1. **Test9ProductID**: Fix the unit test so that a Product object with the right id is generated. The id is calculated the following way.
      - offset: Number added to 222000
      - color code: if 1 it is R, if 2 it is B
      - revision: number added to the end of the id
      - So, the product ID of offset of 111, color code of 2 and revision 3 is "222111B3".

  1. **Test10FindMACAddress**: Fix the unit test so that the function findByMACAddress can find a WirelessAdapter by the MAC address string. It should return the found WirelessAdapter object.
