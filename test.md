ord("A")->65 아스키코드   
chr(65)->A 반대임

.isdigit() -> 숫자인지 True/False   
.isalpha() -> 문자열인지 T/F   
.upper() -> 모두 대문자로 변환   
.capitalize() -> 첫글자만 대문자로 변환   
.title() -> 알파벳 외 문자로 나누어진 경우 첫글자 대문자변환   

.count()


정렬
answer = sorted(sorted(strings), key=lambda x:x[n])

#return sorted(s, reverse=True)  s문자열 정렬->배열로 나열   
 return ''.join(sorted(s, reverse=True))  배열을 문자로 

startswith() 접두어확인


행렬의 덧셈
def solution(arr1, arr2):   
    answer = [[]*len(arr1[0]) for _ in range(len(arr1))]   
    #print(arr1[0][0])   
    for i in range(len(arr1)):   
        for j in range(len(arr1[i])):   
            answer[i].append(arr1[i][j]+arr2[i][j])   
    return answer

이진수로 변경   
format(value, 'b')

중복값 제거    
list(set(ex_list))