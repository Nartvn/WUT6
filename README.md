# WUT6

•	Nĩ hão (xin chào)<br>

---

•	Cho mọi người xem đề bài và dịch đề bài. Đọc đề bài có vẻ như 2 hacker đã trao đổi những bản nhạc với nhau.<br>

* Metarial: Đề bài (```question.jpg```), Đề bài đã dịch (```questionTrans.jpg```)<br>
---
•	Kết quả khi tải file challenge, được 1 file ```mind_tricks.pcap```. Thì pcap hay ```Packet Capture```    mọi người nếu chưa biết về định dạng file này có thể tìm hiểu vể nó trên wiki. Thì em sẽ file bằng ứng dụng wireshark. <br>

* Metarial: ```FileDowload.jpg```
---

•	Khi mở file ra và lọc theo ```tcp.stream eq 8``` có vẻ như được 1 manh mối quan trọng là tần số 2 hacker truyền đạt cho nhau.<br>

* Metarial: ```clues.jpg```

---

•	Tiếp sau đó kiểm tra file từ giao thức SMB(Server Message Block), được 1 file ```Capture the Flag Kings.wav``` có vẻ như flag được giấu trong này (flaginhere.png). Xuất file về kiểm tra được kết quả đây là 1 file dạng âm thanh (soundcheck.png) kết hợp với manh mối đầu tiên tiến hành đem lên ```Audacity``` để kiểm tra tần số ở đó có gì vì đã nghe và không thu được gì.

* Metarial: ```flaginhere.png```, ```soundcheck.png```

---

•	Khi chỉnh tần số từ 18000Hz đến 21000Hz thì ra được hình dạng của flag mà chúng ta đang tìm.

* Metarial: ```flag.png```

---

•	Video demo quá trình giải.

* Metarial : ```video```