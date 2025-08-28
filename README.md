# ReactJS Notes - Day 34 FullStack

## 🌟 ReactJS là gì?

-   **ReactJS**: Một **Library** giúp xây dựng UI nhanh và chuyên nghiệp hơn.

## 🧩 Component

-   Chia nhỏ các thành phần UI.
-   Giúp **dễ quản lý** và **phát triển trong tương lai**.

## 🎣 Hooks

-   Một số hooks cơ bản:

    -   `useState` : cái hộp lưu dữ liệu, thay đổi hộp thì UI tự update.

        -   useState có 2 phần:
        -   count: giá trị hiện tại trong hộp.
        -   setCount: cái chìa khóa để thay đổi giá trị trong hộp.

    -   `useEffect`: người giúp việc, lo những việc bên ngoài sau khi UI vẽ xong.

        -   Hàm callback → việc cần làm.
        -   Mảng dependency [] → khi nào thì làm việc đó.
        -   [] rỗng → chỉ chạy 1 lần lúc component load.
        -   [count] → chạy lại mỗi khi count thay đổi.
        -   Không có [] → chạy lại mỗi lần render (thường không nên).

-   Hooks giống như "móc" gắn thêm tính năng cho component.

## ⚡ Rendering

-   **SSR (Server Side Rendering)**

    -   Tạo HTML hoàn chỉnh ở phía **server**.
    -   Nhanh hơn CSR ở lần tải đầu vì server trả về HTML đã render sẵn.

-   **CSR (Client Side Rendering)**
    -   Tạo HTML ở phía **client**.
    -   Phù hợp cho **Single Page Application (SPA)**.

👉 So sánh:

-   **Multiple Page Application (MPA)** → thường dùng **SSR**.
-   **Single Page Application (SPA)** → thường dùng **CSR** (ReactJS).

## 📦 Props và State

-   **Props**: Dùng để truyền dữ liệu từ ngoài vào component.
-   **State**: Lưu dữ liệu bên trong component → thường hiển thị ra UI.

## ⚛️ JSX

-   JSX được sinh ra để thay thế `React.createElement`.
-   Giúp viết code gần giống HTML nhưng mạnh mẽ hơn.
