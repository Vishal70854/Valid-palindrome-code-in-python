# Valid-palindrome-code-in-python
We have to check valid palindrome for the given string which contains only alphanumeric characters


    def isPalindrome(self, s: str) :
        c=""
        for i in range(len(s)):
            if s[i].isalnum():
                c+=s[i].lower()
               
        return c == c[::-1]
