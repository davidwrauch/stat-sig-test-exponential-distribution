This is an approach to calculate sample size needed for an exponentially distributed variable in an AB test (ie revenue). One cannot use Students or Welch's t-test on exponentially distributed variables. This r code uses the WMWssp package, which requires a sample of the control distribution via sample records. I determined that 10,000 records allowed for a consistently accurate distribuion representation.
