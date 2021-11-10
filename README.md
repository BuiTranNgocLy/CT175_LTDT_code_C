# LÝ THUYẾT ĐỒ THỊ-GRAPH THEORY
## Chương 1. Cơ bản
### 1.1 Các khái niệm cơ bản
- Đồ thị vô hướng và có hướng
- Các thuật ngữ cơ bản
- Một số dạng đồ thị vô hướng đặc biệt

### 1.2 Biểu diễn đồ thị
- Ma trận kề, ma trận trọng số, Ma trận liên thuộc đỉnh
cạnh
- Danh sách cạnh, Danh sách kề

### 1.3 Duyệt đồ thị
- Tìm kiếm theo chiều sâu - DFS
- Tìm kiếm theo chiều rộng - BFS

## Chương 2: Tính liên thông của đồ thị
- Tìm đường đi và kiểm tra tính liên thông
- `Thuật toán Tarjan` - tìm bộ phận liên thông mạnh

## Chương 3: TÌm đường đi ngắn nhất
- Biểu diễn Đồ thị có trọng số
- Bài toán đường đi ngắn nhất
- Phát biểu bài toán
- Đường đi ngắn nhất xuất phát từ một đỉnh
  - `Thuật toán Moore - Dijkstra`
  - `Thuật toán Bellman - Ford`
- Đường đi ngắn nhất trên đồ thị không có chu trình
- Đường đi ngắn nhất giữa mọi cặp đỉnh (Thuật toán Floyd)

## Chương 4: Xếp hạng đồ thị & Tổ chức thi công
- Xếp hạng các đỉnh đồ thị
   - Đồ thị có hướng không chu trình (DAG)
   - Giải thuật xếp hạng đồ thị
- Bài toán tổ chức thi công

## Chương 5. Cây và cây khung của đồ thị
### 5.1 Cây vô hướng
- Cây và các tính chất của cây
- Cây khung của đồ thị
- `Thuật toán Kruskal` - cây khung tối thiểu_bài toán xây dựng
- `Thuật toán Prim`
### 5.2 Cây có hướng
- Cây và các tính chất của cây
- `Thuật toán Chu-Liu/Edmonds` 

## Chương 6. Bài toán luồng cực đại trong mạng
- Mạng, luồng và bài toán luồng cực đại
- Định lý Ford-Fulkerson
- `Thuật toán Ford-Fulkerson`

## Thực hành
### cấu trúc quan trọng khi thực hành
- [Danh sách - List]()
- [Hàng đợi - Queue]()
- [Ngăn xếp - Stack]()
### Buổi 1
[Tài liệu TH]()
- [Bài 1 - Ma trận đỉnh cung(add_edge)]()
- [Bài 2 - Ma trận đỉnh - cung (neighbors)]()
- [Bài 3 - Ma trận đỉnh - đỉnh (degree)]()
- [Bài 4 - Bậc lớn nhất]()
- [Bài 5 - Danh sách cung]()
- [Bài 6 - Đọc đồ thị từ tập tin]()
### Buổi 2
[Tài liệu TH]()
- Bài 1 - Duyệt đồ thị
  - 1.1 Duyệt đồ thị theo chiều rộng (Queue)
  - 1.2 Duyệt đò thị theo chiều sâu (Stack)
  - 1.3 Duyệt đò thị theo chiều sâu (Đệ Quy)  
- Bài 2 - Duyệt đồ thị & Dựng cây duyệt đồ thị
  - 2.1 - Duyệt & dựng đồ thị theo chiều rộng(QUEUE)
  - 2.2 - Duyệt & dựng đồ thị theo chiều sâu(STACK)
  - 2.3 - Duyệt & dựng đồ thị theo chiều sâu(Đệ Quy)
- Bài 3 - Đồ thị liên thông - Qua đảo
- Bài 4 - Tôn Ngộ Không
- Bài 5 - Kiểm tra chu trình - đồ thị vô hướng
- Bài 6 - Thuyền trưởng Haddock
- Bài 7- Phân chia đội bóng
- Bài 8 - Kiểm tra tính liên thông mạnh - đếm số BPLT mạnh
  - 8.1 - Kiểm tra tính liên thông mạnh
  - 8.2 - Đếm số bộ phận liên thông mạnh
- Bài 9 - Come and Go
### Buổi 3
[Tài liệu TH]()
- Bài 1 - Tìm đường đi ngắn nhất
  - 1.1 - Tìm đường đi ngắn nhất - đơn đồ thị có hướng
  - 1.2 - Tìm đường đi ngắn nhất - đơn đồ thị vô hướng
- Bài 2 - Tìm đường đi ngắn nhất (Check được)
  - 2.1 - Kiểm tra chu trình âm - đơn đồ thị có hướng
  - 2.2 - Ứng dụng đường đi ngắn nhất - Ngưu Lang Chức Nữ
- Bài 3 - Kiểm tra chu trình âm và ứng dụng đường đi ngắn nhất
- Bài 4 - Ứng dụng đường đi ngắn nhất
- Bài 5 - Mê cung số (Number Maze)
- Bài 6 - Bellman - Ford pi và pi
- Bài 7 - Bellman - Ford
- Bài 8 - Floyd - Warshall
- Bài 9 - Tìm số đường đi ngắn nhất (nâng cao)
### Buổi 4
[Tài liệu TH]()
- Bài 1- Xếp hạng đồ thị
- Bài 2 - Cân đá
- Bài 3 - Chia kẹo
- Bài 4 - Tổ chức thi công - Dự án xây nhà
- Bài 5 - Tổ chức thi công - Dự án phần mềm
  - 5.1 - Tổ chức thi công - Dự án phần mềm 1
  - 5.2 - Tổ chức thi công - Dự án phần mềm 2
### Buổi 5
[Tài liệu TH]()
- Bài 5.1. Tìm cây khung bằng giải thuật Kruskal
- Bài 5.2. tìm cây khung có trọng lượng nhỏ nhất bằng giải thuật Prim
- Bài 5.3. Tìm luồng cực đại trong mạngTrắc nghiệm
