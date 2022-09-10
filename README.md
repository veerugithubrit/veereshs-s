# veereshs-s



#exaple1: fine the twosum numbers
 #Input: nums = [2,7,11,15], target = 9
 #Output: [0,1]

def twoSum(nums, target):
    for i in range(len(nums)):
        for j in range(i+1,len(nums)):
            if target-nums[i]==nums[j]:
                return[i,j]
    return
test=[2,7,11,15]
target=9
print(twoSum(test,target))            



#exaple2:
 #Input: nums = [3,2,4], target = 6
 #Output: [1,2]
 
def twoSum(nums, target):
    for i in range(len(nums)):
        for j in range(i+1,len(nums)):
            if target-nums[i]==nums[j]:
                return[i,j]
    return
test=[3,2,4]
target=6
print(twoSum(test,target)) 
 
 
 
 
 
 
#exaple3: 
#Input: nums = [3,3], target = 6
#Output: [0,1]
def twoSum(nums, target):
    for i in range(len(nums)):
        for j in range(i+1,len(nums)):
            if target-nums[i]==nums[j]:
                return[i,j]
    return
test=[3,3]
target=6
print(twoSum(test,target)) 
