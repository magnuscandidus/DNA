# DNA
t=int(input())
for i in range(t):
    n=int(input())
    s=input()
    d={'A':'T', 'T':'A', 'C':'G','G':'C'}
    l=''
    for i in range(len(s)):
        if s[i] in d:
            l+=d[s[i]]
    print(l)
