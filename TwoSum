//Brute-Force Solution O(n²)
public class Solution {
    public int[] TwoSum(int[] nums, int target) {
       for (int i =0 ; i<nums.Length ; i++){
        for (int j=i+1 ; j<nums.Length ; j++){
            if (nums[i] + nums[j] ==target){
                return new int[] {i,j};
            }
        }
       }
       return new int[] {};
    }
}
//Optimized One O(n)
public class Solution {
    public int[] TwoSum(int[] nums, int target) {
       Dictionary<int,int> mappingDictionary = new Dictionary<int,int>();
       for(int i=0; i<nums.Length;i++){
        int current = target-nums[i];
        if(mappingDictionary.ContainsKey(current)){
            return new int[] {mappingDictionary[current],i};
        }
        mappingDictionary[nums[i]]=i;
       }
       return new int[] {};
    }
}
