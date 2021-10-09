# junit 5 basics


1. `@Test` Declaring simple test method 
```
@Test
public void myTest(){
    assertEquals(3,3);
}

```

2. `@Ignore` ingnore a test method

```
@Test
@Ignore("for some reason")
public void myTest(){
    assertEquals(3,3);
}

```

3. 