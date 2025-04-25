# FoodImageChat
An AI-integrated application to chat with your Vietnamese food images.
## Giới Thiệu
Hệ thống ứng dụng Deep Learning để nhận diện món ăn từ hình ảnh và tự động gợi ý công thức chế biến món ăn. Người dùng chỉ cần chụp một tấm hình món ăn, hệ thống sẽ xác định đó là món gì và đưa ra hướng dẫn nấu ăn chi tiết.

## Lý Do Tạo Ra Sản Phẩm
Trong thời đại hiện nay, khi người dùng thường xuyên chia sẻ và lưu trữ hình ảnh đồ ăn, nhu cầu biết rõ thông tin món ăn và cách chế biến nó ngày càng tăng. Tuy nhiên, việc tìm kiếm công thức từ hình ảnh thường đòi hỏi thao tác thủ công, gây bất tiện.

### Hệ thống này ra đời với mục tiêu:

Giúp người dùng nhanh chóng xác định món ăn qua hình ảnh.

Cung cấp công thức nấu ăn trực tiếp, không cần phải tìm kiếm nhiều nguồn.

Hỗ trợ người dùng học nấu ăn một cách trực quan và thông minh.

## Kiến Trúc Mô Hình
### 1. Mô hình Nhận Diện Hình Ảnh (Food Classification)
Sử dụng các kiến trúc CNN hiện đại như ResNet, inception, XCeption, CCT4 và ViT.

Huấn luyện trên tập dữ liệu đồ ăn phổ biến của Việt Nam trải dài khắc các miền.

### 2. Mô hình Ngôn Ngữ (Recipe Generator)
Finetung các mô hình ngôn ngữ như Flan, Llama

Tự động sinh ra danh sách nguyên liệu, các bước nấu, mẹo chế biến và thông tin về món ăn.

You can run our Gradio demo [here](https://colab.research.google.com/drive/112nkjr3pcaHSwwsI1SKSMS_OurBVTJ8K?usp=sharing/).
