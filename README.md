Grafana
- Grafana là một vizualizer hiển thị các metric dưới dạng các biểu đồ (chart) hoặc đồ thị (graph), được tập hợp lại thành dashboard có tính tùy biến cao, giúp dễ dàng theo dõi tình trạng của node. Đơn giản cho các bạn dễ hiểu là sau khi lấy được metric từ các thiết bị,grafana sẽ sử dụng metric đó để phân tích và tạo ra dashboard mô tả trực quan các metric cần thiết cho việc monitoring như CPU, RAM, disks, IO operations...

Prometheus
- Prometheus được dùng để giám sát hệ thống thông qua các daemon cài sẵn trên các node, qua đó thu thập các thông tin cần thiết. Prometheus giao tiếp với node qua giao thức http/https và lưu trữ data theo dạng time-series database (TSDB).
- Prometheus sẽ thực hiện quá trình kéo (pull) các thông số/số liệu (metric) từ các job (exporter).
- Prometheus sẽ lưu trữ các dữ liệu thu thập được ở local máy chủ.
- Prometheus sẽ chạy các rule để xử lý các dữ liệu theo nhu cầu cũng như kiểm tra thực hiện các cảnh báo mà bạn mong muốn.
