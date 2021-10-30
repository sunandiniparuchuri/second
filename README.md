# second
def solve(s):
    a_string = s.split(' ')
    k=' '.join((word.capitalize() for word in a_string))
    return k

if __name__ == '__main__':
    fptr = open(os.environ['OUTPUT_PATH'], 'w')

    s = input()

    result = solve(s)

    fptr.write(result + '\n')

    fptr.close()
