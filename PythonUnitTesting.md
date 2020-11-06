![picture 1](images/b1aa586e335547dda092c46d0fede9ddb46f5f666a9e3f4f5fe812f462f31a12.png)  
![picture 3](images/f2f69d93436c688bd29571553298ec349966486279ef0d729a8bf68352db8242.png)  

![picture 4](images/711960caf61a438be0cc2fb78f6c685d0bd3dc81566c4d5935a2880820aa4fd6.png)  
- Each test function must start with *test_*
- To check if function raises proper error:
![picture 6](images/51f99f3926f01ce29266b213959ed1831f06ca1c14254302e9f2367aac0145dc.png)  

### Setup and TearDown
- setUp is executed before every test_function.
- tearDown is executed after every test_function.
![picture 7](images/6bf1fc03a6ced134e8e58bb57c1da059d63c547a0021fbff3fca19f1bc4877db.png)  

- For classes run before and after the whole TestCase.
- Useful for cases when retrieving from database.
- ![picture 8](images/91c1f055c45db65a86ac88201ad9c1e776ebd6e16dcfe7254c7f7d9d59eb2f81.png)  

### Testing in-between the functions
- Mocking.