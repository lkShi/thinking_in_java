Arrays.asList 这种方式可以将一个数组转换成ArrayList，不过这个ArrayList是Arrays的内部类，不可进行add等操作，长度固定
```
    java.utils.Arrays.ArrayList c =   Arrays.asList(0,1,2,3,4,5);
```
可使用如下方式
```
    java.utils.ArrayList array = new ArrayList(Arrays.asList(0,1,2,3,4,5));
```

Arrays.toString();这个方法可以按照 `{1,2,3,4,5}`这种方式输出数组，无需自己手动循环
```
    int[] nums = {1,2,3,4,5};
    Arrays.toString(nums);
```
