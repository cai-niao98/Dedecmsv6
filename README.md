# Dedecmsv6
1. Log in to the website background using the website default password admin/admin
![image](https://user-images.githubusercontent.com/52815221/194448537-3fbbb2d5-c387-4e75-b364-a697cceb9340.png)
2. Visit the csrf attack website,Add an administrator user
![image](https://user-images.githubusercontent.com/52815221/194448553-128ebd4d-b8be-4f8e-b5f1-cae56822585f.png)
![image](https://user-images.githubusercontent.com/52815221/194448569-b7b1281c-16f8-4395-bbe4-ab9e1802e1aa.png)
![image](https://user-images.githubusercontent.com/52815221/194448690-2ee2e63e-6931-4e83-b2fb-29bb8b8e5ba1.png)
3. The user was successfully created but could not log in. There was a problem with the system code. The created users could not log in. After checking the code, we found that the stored password was not the password we entered, but the 6th to 25th digits of the value encrypted by cmd5.
![image](https://user-images.githubusercontent.com/52815221/194449123-358becda-f6b5-441c-a1fc-ca201cd3799d.png)
![image](https://user-images.githubusercontent.com/52815221/194449130-eb28558c-25b1-4ca9-87a4-ea8adc7dfc52.png)
![image](https://user-images.githubusercontent.com/52815221/194449141-7ea74dc8-02f6-43a1-88ce-323f003aeb24.png)
4.Attack content
![image](https://user-images.githubusercontent.com/52815221/194449355-7a88568a-6f49-4fec-ba47-e7998aad4e5b.png)
![image](https://user-images.githubusercontent.com/52815221/194449367-64892605-afc2-43ce-bfc6-9b4d7d240c09.png)
5. The user who created it has a security authentication string for protection, but it does not seem to verify whether it matches the authentication string in the page.
![image](https://user-images.githubusercontent.com/52815221/194449450-0d782fdf-506a-4bf6-94a1-1d512a059028.png)
6. The websites used in this test have not been attacked, and the test users have been deleted.
