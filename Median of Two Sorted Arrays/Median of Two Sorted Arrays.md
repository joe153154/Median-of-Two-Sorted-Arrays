def median_two_array(num1, num2):
    num = num1+num2
    a = len(num)%2
    if a == 1:
        n = len(num)
        m = int(n/2)
        ans = num[m]
    else:
        n = int(len(num)/2)
        m = num[n]+num[n+1]
        ans = m/2
    print(ans)

def main():
    num1 = [1, 5, 8, 10, 11]
    num2 = [12, 14, 15, 19]
    median_two_array(num1, num2)

if __name__ == "__main__":
    main()