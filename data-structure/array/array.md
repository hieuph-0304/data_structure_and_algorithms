#### Static array 
1. Khái niệm
- có độ dài n cố định
- chứa n elements
- indexable: 0 -> n-1 
- cách lưu trữ: 
  + các elemnt sẽ được liên kết với 1 index
  + khi khai báo static array thì ta sẽ khai báo độ dài cố định của nó, thì khi đó nó sẽ tìm trong bộ nhớ, vị trí nào size = size của array thì nó sẽ thả vào đó
  + element thứ 0 là điạ chỉ bắt đầu của array, củng là địa chỉ của array đấy lun.

2. Mục đích
- lưu trữ, truy xuất data có tính liên tục
- IO buffer
- Search table
- Return type

3. So sánh
              Dynamic array | Static array
  - Access:       O(1)      |     O(1)
  - Search:       O(n)      |     O(n)
  - Insertion:    O(n)      |     N/A (không thể thực hiện do độ dài cố định)
  - Appending:    O(1)      |     N/A (không thể thực hiện do độ dài cố định)
  - Deletion:     O(n)      |     N/A (không thể thực hiện do độ dài cố định)

#### Dynamic array 
1. Khái niệm
- có độ dài không cố định
- có thể thêm bớt element được
- cách lưu trữ trong bộ nhớ
  + Ví dụ: arr = [1,2,3,4,5,6,7,8] thì nó sẽ lưu vào 1 vùng nhớ có độ dài chứa đủ 8 element phần tử. 
  + Khi thực hiện add thêm element vào dynamic array.Nếu
    * số lượng vùng nhớ bên cạnh vẫn đủ thì sẽ add thêm element đó vào bên cạnh
    * số lượng vùng nhớ không đủ => sẽ remove dynamic array qua 1 vị trí mới trong bộ nhớ, nơi mà có thể lưu trữ đủ số element

