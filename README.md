# 과제 39    
def b(i):    
  for num in range(0,i+1):    
    if num % 2 != 0:    
      print (num, end=' '"\n")    
  
x = int(input('정수를 입력하세요:'))    
b(x)    

**사용자로부터 양수(숫자)를 입력 받아, 0부터 해당 숫자 포함까지    
홀수인 숫자를 출력하였습니다. user-defined function(사용자 정의 함수)을    
아용하였으며 for 반복문을 통해 출력하였습니다.**    


# 과제 40    
def b(i):    
  for num in range(0,i+1):    
    if num % 3 == 0:    
      print (num, end=' '"\n")    

x = int (input('정수를 입력하세요:'))    
b(x)    

**사용자로부터 숫자를 입력 받아 3의 배수만 출력하는 코드입니다.    
user-defined function(사용자 정의 함수)을 이용하였습니다.**    

# 과제 41    
def b(n1, n2, n3, n4):    

    max = n1    
    min = n1    
  
    if n2 > max:    
        max = n2    
    if n2 < min:    
        min = n2   
    if n3 > max:    
        max = n3    
    if n3 < min:    
        min = n3    
      
    if n4 > max:    
        max = n4    
    if n4 < min:    
        min = n4    
        
    return max, min    

num1 = int(input("첫 번째 숫자를 입력하세요: "))    
num2 = int(input("두 번째 숫자를 입력하세요: "))    
num3 = int(input("세 번째 숫자를 입력하세요: "))    
num4 = int(input("네 번째 숫자를 입력하세요: "))    

max_value, min_value = b(num1, num2, num3, num4)    
    
print(f"최댓값: {max_value}")    
print(f"최솟값: {min_value}")    

**사용자로부터 숫자 4개를 입력 받은 후 최댓값과 최솟값을 계산하였습니다.    
user-defined function(사용자 정의 함수)을 이용하였습니다.    
코드가 너무 길어져 코드 블록도 같이 사용하여 만들어보았습니다.**     

# 과제 42    
def b(i):       
  for num in range(0,i+1):    
    if num % 2 != 0:    
      print (num, end=' '"\n")    
  
x = int (input('정수를 입력하세요:'))    
b(x)    

**사용자로부터 양수(숫자)를 입력 받아, 0부터 해당 숫자 포함까지    
홀수인 숫자를 출력하였습니다. user-defined function(사용자 정의 함수)을    
아용하였으며 for 반복문을 통해 출력하였습니다.**    

# 과제 43    
def b(i):    
  m =1    
  for z in range(1, i+1):     
    m *= z    

  return m    

x = int (input("0보다 크거나 같은 정수 n을 입력하세요: "))    
print (b(x),end='!'"\n")    

**사용자로부터 0보다 크거나 같은 정수 n을 입력 받아 n! (펙토리얼)을    
계산해서 출력하였습니다. user-defined function(사용자 정의 함수)을 이용하였습니다.**     

# 과제 44    
def b(v,z):    
  for i in range(v+1):    
    for j in range(z+1):    
      if ( i * j > 30):    
        print ("%d * %d = %d" % (i,j,i * j))    

v = int(input('2이상 9이하의 숫자를 입력하세요:'))    
z = int(input('2이상 9이하의 숫자를 입력하세요:'))    
b(v,z)    

**사용자로부터 2 이상 9 이하의 양수(숫자) 2개(i, j)를 입력 받아서, 이중 반복문을 돌면서    
i와 j의 곱이 30 이상인 경우의 총 합을 출력하였습니다.    
user-defined function(사용자 정의 함수)을 이용하였습니다.**     

# 과제 45    
def b(z, x, h, n, m):    
  return z + x + h + n + m    

y, u, i, o, p = list(map(int, input('1 2 3 4 5를 입력하세요: ').split()))    
rst = b(y, u, i, o, p)    
print (f"합계: [{rst}]")    

**a = {1, 2, 3, 4, 5] 리스트를 함수의 입력으로 받아서 리스트 값의    
누적 합을 출력하였습니다. user-defined function(사용자 정의 함수)을 이용하였습니다.**    

**감사합니다!**
