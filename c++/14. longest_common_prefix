#include<cstring>
class Solution {
public:
    string longestCommonPrefix(vector<string>& strs) {
        if(strs.size() == 0)
        {
            return "";
        }
        string p = strs[0];
        string prefix ="";
        for(int i = 1;i < strs.size();i++)
        {   
            for(int j = 0; j< p.size() && j< strs[i].size();j++)
            {
                
                if(p[j] == strs[i][j])
                {
                    prefix += p[j];
                    continue;
                }
                else{
                    break;
                }
                
            }
            p = prefix;
            prefix = "";
        }
        return p;
    }
};
