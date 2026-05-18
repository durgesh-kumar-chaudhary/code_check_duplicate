def atleast_twice():  # python code for return true if any  array items have at least twice ,otherwise,if only distnict elements only  return false
    s = set()

    for i in nums:
        if i in s:
            return True
        
        s.add(i)

    return False
