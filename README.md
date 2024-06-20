def pyramid_sort (arr):
    stack = [ ]
    msx_value = None
    while len (stack) > 0:
       max_value = max(stack,key=stack.pop)
       for i in range (len(arr)):
           if arr[i] > max_value:
              stack.append(max_value)
              max_value=arr[j]
              break
    return arr
