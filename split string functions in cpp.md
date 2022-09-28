```cpp
   // with vectors
    std::vector<std::string> split(std::string str, char delim) {
        std::string line;
        std::vector<std::string> res;
        std::stringstream ss(str);
        while (std::getline(ss, line, delim)) res.push_back(line);
        return res;
    }
   // with strings
   void simple_tokenizer(string s)
{
    stringstream ss(s);
    string word;
    while (ss >> word) {
        cout << word << endl;
    }
}
    
