# prime

def is_prime(n):
    if n == 1:
        return False 
    for d in range (2, n):
        if n%d == 0:
            return False 
    return True   
for n in range (1, 100): 
    print (n, is_prime (n))
