bool isNonOverlappingSubstrings(string s)
{
    int p, n = s.size();
    if (n > 2){
        p = s.find("AB");
        if (p != string :: npos && s.substr(p + 2).find("BA") != string :: npos)
            return 1;
        else
            p = s.find("BA");
        if (p != string :: npos && s.substr(p + 2).find("AB") != string :: npos)
            return 1;
    }
    return 0;
}
