# 8051timer

controllerF = 11059200
timeToCount = .00100
leastCount = .000001085
count = timeToCount / leastCount
print('Time To Count : ',timeToCount)
print('Count : ',count)

print('timer mode 00 13 bit means max cont is ',pow(2,13)-1)
requiredCountForReturn = 13
countWeNeedToOperate = pow(2,13)-1-count+requiredCountForReturn
print('Counts to get desired time ', countWeNeedToOperate)
print('Counts to get desired time  in bin ', bin(int(countWeNeedToOperate)))
print('Counts to get desired time  in bin ', hex(int(countWeNeedToOperate)))



print('--------------')
controllerF = 11059200
timeToCount = .00100
leastCount = .000001085
count = timeToCount / leastCount
print('Time To Count : ',timeToCount)
print('Count : ',count)

print('timer mode 00 13 bit means max cont is ',pow(2,16)-1)
requiredCountForReturn = 13
countWeNeedToOperate = pow(2,16)-1-count+requiredCountForReturn
print('Counts to get desired time ', countWeNeedToOperate)
print('Counts to get desired time  in bin ', bin(int(countWeNeedToOperate)))
print('Counts to get desired time  in bin ', hex(int(countWeNeedToOperate)))
