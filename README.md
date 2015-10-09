# advanceTextFiled
IOS Custom Text Filed With Many Types (List ,Numeric,Date) with picker and blocks support 

How To Use
- drag and drop advanceTextFiled.h & advanceTextFiled.m  to your project 
- import advanceTextFiled.h
- go to interface buldier (storyboard) and set advanceTextFiled as class for your textfiled
- get refrence outloet to your conroller 
-in view did load you can set :- 
  Type of textfile for example : 
                        [self.yourTextFiled didendSelect:^(NSInteger index) {
                         NSLog(@"%@",[self.yourTextFiled.listData objectAtIndex:index]);
                          }];
