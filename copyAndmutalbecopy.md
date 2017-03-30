
###  //1.
####  [weakSelf.mData removeAllObjects];
####  weakSelf.mData = [weakSelf.mData_copy mutableCopy];
                    
### //2.
####  [weakSelf.mData removeAllObjects];
####  weakSelf.mData = [weakSelf.mData_copy copy];
 
 ### 第二种方法会在第二次执行该方法是发生崩溃  由此证明 mutableCopy的结果可变 copy的结果不可变
         
 
