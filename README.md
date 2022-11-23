# Jewels-and-Stones-
class Solution {
public:
    int numJewelsInStones(string jewels, string stones) {
        int a=jewels.size();
        int b=stones.size();
        int c=0;
        for(int i=0;i<a;i++){
            for(int j=0;j<b;j++){
                if(jewels[i]==stones[j]){
                    c+=1;
                    
                }
            }
        }
        return c;
        
    }
};
