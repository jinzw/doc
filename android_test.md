写android Activity的测试用例时，继承ActivityInstrumentationTestCase2时，必须要实现无参的构造函数，否则会报异常
```
junit.framework.AssertionFailedError: Class package.FooTest has no public constructor TestCase(String name) or TestCase()
at android.test.AndroidTestRunner.runTest(AndroidTestRunner.java:190)
```
