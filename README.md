# junit 5 basics


1. Declaring simple test method `@Test`
```
@Test
public void myTest(){
    assertEquals(3,3);
}

```

2. Ignore a test method

```
@Test
@Ignore("for some reason")
public void myTest(){
    assertEquals(3,3);
}

```