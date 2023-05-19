# Instagram

:house:**Instagram**

### ***Framework***
---------
- spring boot

-------------

### ***Project management tool***
-------
- Maven


-----------------
### ***DataBase***
****************
- MySql
****************

### **use of dependency**
-----
- <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-data-jpa</artifactId>
      </dependency>
- <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-web</artifactId>
     </dependency>

- <dependency>
       <groupId>org.springframework.boot</groupId>
       <artifactId>spring-boot-devtools</artifactId>
	<scope>runtime</scope>
	<optional>true</optional>
	</dependency>
- <dependency>
    <groupId>com.mysql</groupId>
    <artifactId>mysql-connector-j</artifactId>
    <version>8.0.33</version>
 </dependency>

- <dependency>
       <groupId>org.projectlombok</groupId>
       <artifactId>lombok</artifactId>
       <optional>true</optional>
	</dependency>
- <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-test</artifactId>
     <scope>test</scope>
     </dependency>
<!-- https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation -->
- <dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-validation</artifactId>
	<version>3.0.6</version>
	</dependency>





--------


-------------


### **Run tests**

------

⭕ postman 

:globe_with_meridians: chrome browser

********

### **Data structure And programming language**

-----

 - core java
 
 --------

  :point_down: **Summary**
*****
 User:
Represents a user of the application.
Contains properties such as userId, firstName, lastName, instagramName, instagramBio, password, dOB (date of birth), email, phoneNumber, and isBlueTicked.
Uses annotations for validation and database mapping.
Post:

Represents a post made by a user.
Contains properties such as postId, createdDate, postData, postCaption, location, and user.
Uses annotations for validation and database mapping.
Has a Many-to-One relationship with the User class.
PostLike:

Represents a like on a post.
Contains properties such as likeId, post, and user.
Uses annotations for database mapping.
Has a Many-to-One relationship with both the Post and User classes.
InstagramFollowing:

Represents the relationship between a user and the users they follow.
Contains properties such as followingTableId, user, and following.
Uses annotations for database mapping.
Has a One-to-One relationship with the User class.
InstagramFollower:

Represents the relationship between a user and their followers.
Contains properties such as followerTableId, user, and follower.
Uses annotations for database mapping.
Has a One-to-One relationship with the User class.
InstagramComment:

Represents a comment on a post.
Contains properties such as commentId, commentBody, post, and user.
Uses annotations for database mapping.
Has a Many-to-One relationship with both the Post and User classes.
Admin:

Represents an administrator of the application.
Contains properties such as adminId, firstName, lastName, and email.
Uses annotations for validation and database mapping.
*****

### **Show your Support** 
****
:star: Thankyou 

****
