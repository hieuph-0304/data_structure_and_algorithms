- Đệ quy là 1 cách giải quyết vấn đề bằng cách gọi lại chính nó
- Mỗi lần function đệ quy gọi lại chính nó gọi là bậc đệ quy
- Mỗi bậc đệ quy nó sẽ đẩy function đệ quy => có thể bị Stack overflow

### Lợi ích: 
- Code ngắn gọn, dễ hiểu

### Recursion
- Termination: Base case is reached
- Memory: Each recursion step require more memory
- Infinite: StackOverflowException

### Loop
- Termination: false condition
- Memory: Each loop step don 't require more memory
- Infinite: Just run and no exception

### Trường hợp sữ dụng đệ quy
- Algorithms: Quick sort and Merge sort, chia để trị
- Data structures: tree, graph
- Dynamic programing
