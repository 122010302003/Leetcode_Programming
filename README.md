# Move Zeroes from an array nums[]

#CODE for the Problem:
#---------------------------------
for x in range(len(nums)):
    for i in range(len(nums)):
        if nums[i]==0:
            app=nums.pop(i)
            nums.append(app)
#---------------------------------
