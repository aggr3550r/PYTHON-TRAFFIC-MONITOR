# PYTHON-TRAFFIC-MONITOR
A mini project that uses Pusher, Flask and JS to monitor traffic to a website and relay realtime updates
UNIT TESTING - Best practices and guidelines

1) NAMING - Naming the tests

The name of the test should consist of 3 parts:

- The name of the method being tested
- The scenario for which it is being tested
- The expected behaviour when that scenario is invoke

```public class Add_SingleNumber_ReturnsSameNumber() {
    var stringCalculator = new StringCalculator();

    var actual = stringCalculator.Add("0");

    Assert.Equal(0, actual);
}
```

2) STRUCTURE - Arrange your tests

The _Arrange, Act, Assert_ structure should be used for
ease of readability




