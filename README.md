Create requests in Postman.

Protocol: http
IP: 162.55.220.72
Port: 5005

EP_1
Method: GET
EndPoint: /get_method
request url params: 
 name: str
 age: int

response: 
[
    “Str”,
    “Str”
]

<img width="842" alt="Screenshot 2022-06-17 at 14 00 37" src="https://user-images.githubusercontent.com/106442178/174358341-60872104-2c0f-4823-8c23-99fcb62f5030.png">

EP_2
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}
                     
           <img width="1006" alt="Screenshot 2022-06-17 at 16 08 35" src="https://user-images.githubusercontent.com/106442178/174358406-259f7435-a8da-4148-80ee-4cbb0827d160.png">

P_3
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int

response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}
          <img width="1008" alt="Screenshot 2022-06-17 at 16 12 57" src="https://user-images.githubusercontent.com/106442178/174358471-c1f9bb6c-912c-4b51-bc45-ef6834f76414.png">

EP_4
Method: GET
EndPoint: /object_info_2
request url params: 
 name: str
 age: int
 salary: int

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
![Uploading Screenshot 2022-06-17 at 16.25.11.png…]()

EP_5
Method: GET
EndPoint: /object_info_3
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'pets': {'cat':{'name':'Sunny',
                                     'age': 3},
                              'dog':{'name':'Luky',
                                     'age': 4}},
                     'u_salary_1_5_year': salary * 4}
          }

<img width="1005" alt="Screenshot 2022-06-17 at 16 32 12" src="https://user-images.githubusercontent.com/106442178/174358605-2d499f96-2242-414a-ac64-fb90d88bc595.png">

EP_6
Method: GET
EndPoint: /object_info_4
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2), str(salary * 3)]}
          
          <img width="1004" alt="Screenshot 2022-06-17 at 16 36 02" src="https://user-images.githubusercontent.com/106442178/174358666-514759e5-44c6-4081-b5fe-da6efad81ee3.png">

EP_7
Method: POST
EndPoint: /user_info_2
request form data: 
 name: str
 age: int
 salary: int

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
<img width="999" alt="Screenshot 2022-06-17 at 16 38 03" src="https://user-images.githubusercontent.com/106442178/174358721-2fde1a88-11c8-4406-90f4-9cdbb8713bd2.png">

Run Collection


          <img width="1038" alt="Screenshot 2022-06-17 at 20 16 29" src="https://user-images.githubusercontent.com/106442178/174358939-17b53c79-bc66-4edd-b54a-1fb3e16d0916.png">

