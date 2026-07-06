# Checking Duplicates in a List

class Solution:
    def containsDuplicate(self, nums):
        # Sort the list in-place (mutates the original list)
        nums.sort()
        # Loop up to the second-to-last element
        for i in range(len(nums) - 1):
            # If adjacent elements are equal, we found a duplicate
            if nums[i] == nums[i + 1]:7
                return True
        return False

nums = [2, 5, 7, 10, 15, 5]
solution = Solution()
print(solution.containsDuplicate(nums))
