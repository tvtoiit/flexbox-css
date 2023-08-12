1. display: flex | inline-flex
- Quyết định có sử dụng flexbox hay không
2. flex-direction: row | column
- thay đổi được phương hướng của main axit
- nếu display: flex; thì flex-direciton: row
- Muốn đảo lại thì dùng: column
3. flex-wrap: nowrap | wrap | wrap-reverse
- wrap: xuống dòng đủ item trên 1 hàng thì xuống dòng
- wrap-reverse: nhảy lên trên, lúc này đảo cross start và cross end
4. flex-basis: <length>
- xét được kích thước của mainsize
- tùy vào trục chính của chúng ta ở phương hướng nào. (cùng chiều với main axit) 

5. justify-content: flex-start | flex-end | center | space-between | space-around
- canh các item trái hay phải, giữa trong trường hợp mainaxit nằm ngang 
- nếu main axit nằm dọc thì canh trên, dưới, giữa

6. justify-self: flex-start | flex-end | center
- con của justify-content nếu cha đã xét thì con không cần xét
7. align-content: flex-start | flex-end | center
- canh được các item theo trục cross axis

8. align-self: flex-start | flex-end | center
- Tương tự: nếu thằng cha đã xét align-content thì tương tự như việc xét align-self cho các item con
9. flex-grow: <number>
- Tăng được kích thước của main size của flex item
10. flex-shrink: <number>
- Ngược lại với flex- grow
11. flex: <number>
cú pháp viết ngắn của: flex-basis, flex-grow, flex-shrink

12. flex-flow: 
cú pháp ngắn của flex-direction và flex-wrap
13. order: <number>
- Quyết định được filex item phần tử nào được hiển thị trước, sau.