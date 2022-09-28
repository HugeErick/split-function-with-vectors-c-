```cpp
class Solution {
public:
    std::vector<std::string> split(std::string str, char delim) {
        std::string line;
        std::vector<std::string> res;
        std::stringstream ss(str);
        while (std::getline(ss, line, delim)) res.push_back(line);
        return res;
    }
    ```
