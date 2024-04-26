## Spring in action
Chaper 01- Getting started with Spring
1.1 What is Spring?
1.2 Initializing a Spring application
1.2.1 Initializing a Spring project with Spring Tool Suite
1.2.2 Examining the Spring project structure
1.3 Writing a Spring application
1.3.1 Handling web requests
1.3.2 Defining the view
1.3.3 Testing the controller
1.3.4 Building and running the application
1.3.5 Getting to know Spring Boot DevTools
1.3.6 Let’s review
1.4 Surveying the Spring landscape
1.4.1 The core Spring Framework
1.4.2 Spring Boot
1.4.3 Spring Data
1.4.4 Spring Security
1.4.5 Spring Integration and Spring Batch
1.4.6 Spring Cloud
1.4.7 Spring Native
Summary
Chapter 02 - Developing web Applications
2.1 Displaying information
2.1.1 Establishing the domain
2.1.2 Creating a controller class
2.1.3 Designing the view
2.2 Processing form submission
2.3 Validating form input
2.3.1 Declaring validation rules
2.3.2 Performing validation at form binding
2.3.3 Displaying validation errors
2.4 Working with view controllers
2.5 Choosing a view template library
2.5.1 Caching templates
Summary
Chapter 03 -Working with data
3.3 Persisting data with Spring Data JPA
3.3.1 Adding Spring Data JPA to the project
3.3.2 Annotating the domain as entities
3.3.3 Declaring JPA repositories
3.3.4 Customizing repositories
Chapter 04 - Working with nonrelational data
4.1 Working with Cassandra repositories
4.1.1 Enabling Spring Data Cassandra
4.1.2 Understanding Cassandra data modeling
4.1.3 Mapping domain types for Cassandra persistence
4.1.4 Writing Cassandra repositories
Chapter05 - Securing Spring
5.1 Enabling Spring Security
5.2 Configuring authentication
5.2.1 In-memory user details service
5.2.2 Customizing user authentication
5.3 Securing web requests
5.3.1 Securing requests
5.3.2 Creating a custom login page
5.3.3 Enabling third-party authentication
5.3.4 Preventing cross-site request forgery
5.4 Applying method-level security
5.5 Knowing your user
Chapter 06 - Working with configuration properties
6.1 Fine-tuning autoconfiguration
6.1.1 Understanding Spring’s environment abstraction
6.1.2 Configuring a data source
6.1.3 Configuring the embedded server
6.1.4 Configuring logging
6.2 Creating your own configuration properties
6.2.1 Defining configuration property holders
6.2.2 Declaring configuration property metadata
6.3 Configuring with profiles
6.3.1 Defining profile-specific properties
6.3.2 Activating profiles
6.3.3 Conditionally creating beans with profiles
Chapter 07-Creating REST services
7.1 Writing RESTful controllers
7.1.1 Retrieving data from the server
7.1.2 Sending data to the server
7.1.3 Updating data on the server
7.1.4 Deleting data from the server
7.2 Enabling data-backed services
7.2.1 Adjusting resource paths and relation names
7.3 Consuming REST services
7.3.1 GETting resources
7.3.2 PUTting resources
7.3.3 DELETEing resources
7.3.4 POSTing resource data
Chapter 8 -Securing REST
8.1 Introducing OAuth 2
8.2 Creating an authorization server
8.3 Securing an API with a resource server
8.4 Developing the client
Chapter 09 - Sending messages Asynchronously
9.1 Sending messages with JMS
9.1.1 Setting up JMS
9.1.2 Sending messages with JmsTemplate
9.1.3 Receiving JMS messages
9.3 Messaging with Kafka
9.3.1 Setting up Spring for Kafka messaging
9.3.2 Sending messages with KafkaTemplate
9.3.3 Writing Kafka listeners
Chapter 10 -Integrating Spring
10.1 Declaring a simple integration flow
10.1.1 Defining integration flows with XML
10.1.2 Configuring integration flows in Java
10.1.3 Using Spring Integration’s DSL configuration
10.2 Surveying the Spring Integration landscape
10.2.1 Message channels
10.2.2 Filters
10.2.3 Transformers
10.2.4 Routers
10.2.5 Splitters
10.2.6 Service activators
10.2.7 Gateways
10.2.8 Channel adapters
10.3 Creating an email integration flow
Chapter 11- Introducing Reactor
11.1 Understanding reactive programming
11.2 Getting started with Reactor
11.2.1 Diagramming reactive flows
11.2.2 Adding Reactor dependencies
11.3 Applying common reactive operations
11.3.1 Creating reactive types
11.3.2 Combining reactive types
11.3.3 Transforming and filtering reactive streams
11.3.4 Performing logic operations on reactive types
Chapter 12 - Developing reactive APIs
12.1 Working with Spring WebFlux
12.1.1 Introducing Spring WebFlux
12.1.2 Writing reactive controllers
12.2 Defining functional request handlers
12.3 Testing reactive controllers
12.3.1 Testing GET requests
12.3.2 Testing POST requests
12.3.3 Testing with a live server
12.4 Consuming REST APIs reactively
12.4.1 GETting resources
12.4.2 Sending resources
12.4.4 Handling errors
12.5 Securing reactive web APIs
12.5.1 Configuring reactive web security
12.5.2 Configuring a reactive user details service
Chapter 13- Persisting data reactively
13.1 Working with R2DBC
13.1.1 Defining domain entities for R2DBC
13.1.2 Defining reactive repositories
13.1.3 Testing R2DBC repositories
13.1.4 Defining an OrderRepository aggregate root service
13.2 Persisting document data reactively with MongoDB
13.3 Reactively persisting data in Cassandra
13.3.1 Defining domain classes for Cassandra persistence
13.3.2 Creating reactive Cassandra repositories
13.3.3 Testing reactive Cassandra repositories
Chapter 14 - Working with Rsocket
14.1 Introducing RSocket
14.2 Creating a simple RSocket server and client
14.2.1 Working with request-response
14.2.2 Handling request-stream messaging
14.2.3 Sending fire-and-forget messages
14.2.4 Sending messages bidirectionally
14.3 Transporting RSocket over WebSocket

## grokking algorithms
ch01: Introduction to algorithm
• Tìm kiếm nhị phân nhanh hơn nhiều so với tìm kiếm đơn giản khi mảng của bạn trở nên lớn.
• O(log n) nhanh hơn O(n), nhưng nó trở nhanh hơn rất nhiều khi danh sách các mục bạn đang tìm kiếm lớn lên.
• Tốc độ của thuật toán không được đo bằng giây.
• Thời gian của thuật toán được đo dưới góc độ sự tăng của một thuật toán.
• Thời gian của thuật toán được viết bằng ký hiệu Big O.

ch02: Selection sort
• Bộ nhớ của máy tính của bạn giống như một bộ sưu tập hộp lớn.
• Khi bạn muốn lưu trữ nhiều phần tử, hãy sử dụng một mảng hoặc danh sách liên kết.
• Trong một mảng, tất cả các phần tử của bạn được lưu trữ ngay bên cạnh nhau.
• Trong một danh sách liên kết, các phần tử được phân tán khắp nơi và một phần tử lưu địa chỉ của phần tử tiếp theo.
• Mảng cho phép đọc nhanh.
• Danh sách liên kết cho phép thêm và xóa nhanh.

ch03: Recursion: 
- Đệ quy là khi một hàm gọi chính nó.
- Mọi hàm đệ quy đều có hai trường hợp: trường hợp cơ sở và trường hợp đệ quy.
- Một ngăn xếp có hai thao tác: đẩy (push) và lấy ra (pop).
- Tất cả các cuộc gọi hàm được đặt lên ngăn xếp gọi (call stack).
- Ngăn xếp gọi có thể trở nên rất lớn, chiếm nhiều bộ nhớ.

ch04: Quicksort: 
- Chia để trị (D&C) hoạt động bằng cách chia một vấn đề thành các phần nhỏ hơn và nhỏ hơn. Nếu bạn đang sử dụng D&C trên một danh sách, trường hợp cơ bản có thể là một mảng trống hoặc một mảng chỉ có một phần tử. Nếu bạn đang thực hiện thuật toán quicksort, hãy chọn một phần tử ngẫu nhiên làm trục. Thời gian chạy trung bình của quicksort là O(n log n)!
- Hệ số trong một hàm đôi khi quan trọng. Nếu có hai thuật toán có cùng thời gian chạy big-O, một có thể luôn nhanh hơn so với thuật toán khác. Đó là lý do tại sao quicksort nhanh hơn merge sort.
- Hệ số hầu như không quan trọng đối với tìm kiếm đơn giản so với tìm kiếm nhị phân, vì O(log n) nhanh hơn rất nhiều so với O(n) khi danh sách của bạn trở nên lớn.

ch05: Hash tables
Bảng băm là một cấu trúc dữ liệu mạnh mẽ vì chúng rất nhanh và cho phép bạn mô phỏng dữ liệu theo một cách khác. Bạn có thể sớm nhận ra rằng bạn đang sử dụng chúng liên tục:
- Bạn có thể tạo một bảng băm bằng cách kết hợp một hàm băm với một mảng.
- Va chạm là xấu. Bạn cần một hàm băm giảm thiểu va chạm.
- Bảng băm có tìm kiếm, chèn và xóa rất nhanh.
- Bảng băm tốt để mô phỏng mối quan hệ từ một mục đến một mục khác.
- Khi tỷ lệ tải của bạn lớn hơn 0.7, đến lúc thay đổi kích thước bảng băm.
- Bảng băm được sử dụng để lưu trữ dữ liệu cache (ví dụ, với một máy chủ web).
- Bảng băm tuyệt vời để phát hiện trùng lặp.

ch06: Breadth-first-search
- Breadth-first search thông báo xem có đường đi từ A đến B hay không.
- Nếu có một đường đi, breadth-first search sẽ tìm đường đi ngắn nhất.
- Nếu bạn có một vấn đề như "tìm đường đi ngắn nhất đến X," hãy cố gắng mô hình hóa vấn đề của bạn dưới dạng đồ thị và sử dụng breadth-first search để giải quyết.
- Một đồ thị có hướng có mũi tên, và mối quan hệ theo chiều của mũi tên (rama -> adit có nghĩa là "rama nợ adit tiền").
- Đồ thị vô hướng không có mũi tên, và mối quan hệ diễn ra cả hai chiều (ross - rachel có nghĩa là "ross hẹn hò với rachel và rachel hẹn hò với ross").
- Hàng đợi là FIFO (First In, First Out).
- Ngăn xếp là LIFO (Last In, First Out).
- Bạn cần kiểm tra người dùng theo thứ tự họ được thêm vào danh sách tìm kiếm, vì vậy danh sách tìm kiếm cần là một hàng đợi. Nếu không, bạn sẽ không có được đường đi ngắn nhất.
- Sau khi kiểm tra một người, hãy đảm bảo bạn không kiểm tra họ lại. Nếu không, bạn có thể rơi vào vòng lặp vô hạn.

ch07: Trees
• Cây là một loại đồ thị, nhưng cây không có chu kỳ.
• Depth-first search là một thuật toán duyệt đồ thị khác. Nó không thể được sử dụng để tìm đường đi ngắn nhất.
• Cây nhị phân là một loại cây đặc biệt nơi các nút có thể có tối đa hai con.
• Có nhiều loại mã hóa ký tự khác nhau. Unicode là tiêu chuẩn quốc tế, và UTF-8 là mã hóa Unicode phổ biến nhất.

ch08: Balanced trees
• Cây tìm kiếm nhị phân cân bằng (BSTs) cung cấp hiệu suất tìm kiếm big-O tương đương với mảng, với hiệu suất chèn tốt hơn.
• Độ cao của một cây ảnh hưởng đến hiệu suất của cây.
• Cây AVL là một loại phổ biến của BST cân bằng. Như hầu hết các cây cân bằng khác, cây AVL tự cân bằng thông qua các phép xoay.
• B-Tree là các BST tổng quát generalized, nơi mỗi node có thể có nhiều khóa và nhiều child node.
• Thời gian tìm kiếm giống như thời gian di chuyển đến cửa hàng thực phẩm. B-Tree cố gắng giảm thiểu thời gian tìm kiếm bằng cách đọc nhiều dữ liệu trong một lần.

ch09: Dijkstra's algorithm
- Breadth-first search được sử dụng để tính toán đường đi ngắn nhất cho
- một đồ thị không có trọng số unweighted graph.
- Thuật toán của Dijkstra được sử dụng để tính toán đường đi ngắn nhất cho
- một đồ thị có trọng số weighted graph.
- Thuật toán của Dijkstra hoạt động khi tất cả các trọng số đều không âm.
- Nếu có trọng số âm, sử dụng thuật toán Bellman-Ford.

ch10: Greedy algorithms
• Thuật toán tham lam (greedy algorithms) tối ưu hóa cục bộ, hy vọng sẽ đạt được giá trị tối ưu toàn cầu.
• Một vấn đề thuộc P nếu nó vừa nhanh chóng giải quyết vừa nhanh chóng xác minh.
• Một vấn đề thuộc NP nếu nó khó giải quyết nhưng lại nhanh chóng xác minh.
• Nếu chúng ta tìm thấy một thuật toán nhanh (thời gian đa thức) cho mọi vấn đề trong NP, thì P = NP.
• Một vấn đề thuộc NP-Hard nếu bất kỳ vấn đề nào trong NP đều có thể được giảm bớt về vấn đề đó.
• Nếu một vấn đề thuộc cả NP và NP-Hard, nó là NP-complete.
• Nếu bạn đối mặt với một vấn đề NP-Hard, lựa chọn tốt nhất là sử dụng một thuật toán xấp xỉ (approximation algorithm).
• Thuật toán tham lam dễ viết và chạy nhanh, vì vậy chúng làm approximation algorithm tốt.

ch11: Dynamic programming
• Quy hoạch động hữu ích khi bạn cố gắng tối ưu hóa một điều gì đó dưới ràng buộc nào đó.
• Bạn có thể sử dụng quy hoạch động khi vấn đề có thể được chia thành các bài toán con rời rạc.
• Mọi giải pháp quy hoạch động đều liên quan đến một lưới.
• Các giá trị trong các ô thường là điều bạn đang cố gắng tối ưu hóa.
• Mỗi ô là một bài toán con, vì vậy hãy suy nghĩ về cách bạn có thể chia vấn đề của mình thành các bài toán con.
• Không có một công thức duy nhất để tính toán một giải pháp quy hoạch động.



## Spring Boot in practice
ch01: booting spring boot
- Spring Boot là gì và lợi ích mà nó mang lại so với một ứng dụng Spring truyền thống.
- Các tính năng của Spring Boot và các thành phần khác nhau của nó.
- Cấu trúc và các thành phần của một dự án Spring Boot được tạo ra.
- Cách tạo một tệp JAR thực thi từ một dự án Spring Boot và cấu trúc của tệp JAR được tạo ra.
- Cách tắt ứng dụng Spring Boot đang chạy một cách trôi chảy.
- Các sự kiện khởi động Spring Boot và các cách khác nhau để lắng nghe các sự kiện này.
- Tổng quan về custom starter, autoconfiguration, failure analyzers và actuators.
- Giới thiệu về các công cụ phát triển Spring Boot để tăng năng suất phát triển.

ch02: common spring boot tasks
- Nhiều cách tiếp cận quản lý thuộc tính ứng dụng trong một ứng dụng Spring Boot.
- Cách sử dụng @ConfigurationProperties để định nghĩa các thuộc tính một cách an toàn theo kiểu.
- Cách cấu hình CommandLineRunner để thực hiện mã thực thi một lần khi ứng dụng Spring Boot khởi chạy.
- Ghi log mặc định trên console của Spring Boot, cấu hình bổ sung và cách sử dụng log Log4j2 trong một ứng dụng Spring Boot.
- Cách sử dụng API Bean Validation để xác nhận POJO trong ứng dụng Spring Boot của bạn với các chú thích tích hợp sẵn cũng như với các chú thích tùy chỉnh.

ch03: introducing spring data
- Bạn đã được giới thiệu về Spring Data, lý do tại sao nó cần thiết và các mô-đun khác nhau của Spring Data.
- Bạn có thể cấu hình cơ sở dữ liệu quan hệ và cơ sở dữ liệu NoSQL với Spring Boot.
- Bạn có thể khởi tạo schema cơ sở dữ liệu với schema.sql và data.sql cũng như thông qua Spring Data JPA.
- Bạn đã hiểu về các giao diện Spring Data CrudRepository và PagingAndSortingRepository cũng như cách sử dụng chúng trong ứng dụng Spring Boot.
- Bạn có thể truy cập dữ liệu từ cơ sở dữ liệu quan hệ bằng cách sử dụng các phương thức truy vấn, @Named-Query, @Query, Criteria API và Querydsl.
- Bạn biết cách quản lý mối quan hệ many-to-many giữa các đối tượng domain trong ứng dụng Spring Boot.

ch04: autoconfiguration & actuator
- Chúng ta đã có một cuộc thảo luận sâu rộng về Spring Boot autoconfiguration. Chúng ta đã khám phá các conditional annotations đóng vai trò quan trọng trong việc triển khai autoconfiguration và tìm hiểu về một built-in class, DataSourceAutoConfiguration, để hiểu cách nó hoạt động trong ứng dụng Spring Boot.
- Chúng ta đã thảo luận về Spring Boot DevTools, cung cấp một bộ tính năng cho trải nghiệm phát triển dễ chịu. Automatic application restart, disabling caching và làm mới trình duyệt là một số tính năng đáng chú ý.
- Chúng ta đã khám phá Spring Boot FailureAnalyzer và vai trò của nó trong việc xác nhận các vấn đề khởi động ứng dụng khác nhau. Chúng ta cũng thảo luận về cách triển khai một FailureAnalyzer tùy chỉnh.
- Chúng ta đã có một cuộc thảo luận sâu rộng về Spring Boot actuator và các endpoint khác nhau của nó. Sau đó, chúng ta đã khám phá các endpoint /info và /health một cách chi tiết hơn. Chúng ta cũng đã học một số kỹ thuật để định nghĩa và bao gồm thông tin ứng dụng tùy chỉnh và trạng thái sức khỏe trong các endpoint này.
- Chúng ta đã khám phá các metric tích hợp của Spring Boot. Chúng ta cũng đã thảo luận về cách tạo ra các metric tùy chỉnh như Counter, Gauge, Timer và Distribution Summary. Cuối cùng, chúng ta đã thực hiện cách sử dụng Prometheus và Grafana để giám sát và xem các metric trong một bảng điều khiển GUI theo thời gian thực.

ch05: Security Spring boot application
- Chúng ta đã tìm hiểu về Spring Security, kiến trúc của nó và tự động cấu hình cho Spring Security trong Spring Boot.
- Chúng ta đã thảo luận về cách triển khai Spring Security trong một ứng dụng Spring Boot và tùy chỉnh trang đăng nhập người dùng.
- Chúng ta đã khám phá cách triển khai authentication trong bộ nhớ, JDBC và LDAP với Spring Security.
- Chúng ta đã thảo luận về cách triển khai kiểm soát truy cập dựa trên vai trò trong ứng dụng Spring Boot.
- Chúng ta đã học cách triển khai xác thực HTTP basic để xác thực người dùng trong một ứng dụng Spring Boot.

ch06: Implementing additional security with Spring security
- Chúng tôi đã kích hoạt HTTPS trong ứng dụng Spring Boot với self-signed certificate và triển khai chuyển hướng tất cả các yêu cầu HTTP sang HTTPS.
- Chúng tôi triển khai Hashicorp Vault để externalize các bí mật ứng dụng trong vault và kết nối ứng dụng Spring Boot với vault để truy cập bí mật.
- Chúng tôi triển khai một mô-đun đăng ký người dùng và kích hoạt xác nhận tài khoản người dùng qua email.
- Chúng tôi kích hoạt một tính năng ứng dụng tạm thời đình chỉ tài khoản người dùng sau nhiều lần đăng nhập không chính xác.

- Chúng tôi kích hoạt tính năng Remember me để đăng nhập nhanh chóng từ các thiết bị tin cậy.
- Chúng tôi triển khai Google reCAPTCHA để ngăn chặn bot internet và cuộc tấn công spam.
- Chúng tôi kích hoạt xác thực hai yếu tố với Google Authenticator để tăng cường bảo mật ứng dụng.
- Chúng tôi triển khai đăng nhập OAuth2 trong ứng dụng Spring Boot với Google.
- Chúng tôi đã học cách bảo vệ các điểm cuối Spring Boot Actuator khỏi việc truy cập không được ủy quyền với Spring Security.


## Reactive Spring
Chapter 1. Introduction
Chapter 2. Prerequisites
2.1. Who this book is for
2.2. What you need for this book
2.3. Conventions
2.4. Reader feedback
2.5. Getting the Code
2.6. Building the Code
2.7. Running the Code
2.8. Some Foundational Java
2.8.1. Type Inference
2.8.2. Function Interfaces, Lambdas and Method References
2.8.3. Lombok
Chapter 3. Bootstrap
Chapter 4. IO, IO, It’s Off to Work We Go…
4.1. A Natural Limit
4.2. Phép ẩn dụ còn thiếu
4.3. The Reactive Streams Initiative
4.4. Are We There Yet?
4.5. Towards a More Functional, Reactive Spring
Chapter 5. Reactor
5.1. The Reactive Streams Specification
5.2. Project Reactor
5.3. Creating New Reactive Streams
5.4. Processors
5.5. Operators
5.5.1. Transform
5.5.2. Do This and Then That
5.5.3. Map
5.5.4. FlatMap and ConcatMap
5.5.5. SwitchMap
5.5.6. Take and Filter
5.5.7. The DoOn* Callbacks
5.5.8. Taking Control of Your Streams' Destiny
5.6. Operator Fusion
5.7. Schedulers and Threads
5.8. Hot and Cold Streams
5.9. Context
5.10. Control Flow
5.10.1. Error Handlers
5.10.2. Retry
5.10.3. Merge
5.10.4. Zip
5.10.5. Timeout and First
5.11. Debugging
5.12. Next Steps
Chapter 6. Data Access
6.1. Why Should You Go Reactive?
6.2. What About Transactions?
6.3. Reactive SQL Data Access
6.3.1. Reactive Relational Database Connectivity (R2DBC)
6.3.2. Making a Connection
6.3.3. The Database Schema
6.3.4. The Repository Interface
6.3.5. The Customer Entity
6.3.6. Tests
6.3.7. Spring Data R2DBC
6.4. More Efficient, Reactive Data Access in NoSQL Pastures
6.4.1. Reactive Transactions in R2DBC
6.4.2. MongoDB
6.4.3. Basic Spring Data MongoDB
Chapter 7. HTTP
7.1. HTTP Works
7.1.1. HTTP Requests
7.1.2. HTTP Responses
7.1.3. HTTP Aims to Serve… Pages
7.2. HTTP Scales
7.3. REST
7.4. Spring WebFlux: a Net-New Reactive Web Runtime
7.4.1. A Simple Sample
7.4.2. Building Spring MVC-Style HTTP Endpoints
7.4.3. Functional Reactive Endpoints
7.4.4. Filters
7.5. Long-Lived Client Connections
7.6. Server-Sent Events (SSE)
7.7. Websockets
7.7.1. Echos of Websockets Past
7.7.2. The Chatastic Websocket Example
7.8. Reactive Views with Thymeleaf
7.8.1. How Spring’s View Resolution Works with Thymeleaf
7.8.2. A Simple HTML View with a Reactive Stream
7.8.3. A Reactive View
7.9. A Reactive Servlet Container
7.10. The Reactive Client
7.10.1. An HTTP Endpoint
7.10.2. Take a Walk on the Client-Side
7.10.3. It’s Your (HTTP) Call
7.10.4. Teaching Your WebClient New Tricks
7.11. Security
7.12. Next Steps
Chapter 8. Testing
8.1. How I Stopped Worrying and Learned to Love Testing
8.2. Test Driven Development
8.3. Inside-Out or Outside-In
Chapter 9. Rsocket
9.1. Motivations for Rsocket
9.1.1. HTTP or Not HTTP
9.1.2. RSocket: A Reactive Network Protocol
9.2. Common Infrastructure for Raw RSocket
9.3. Raw Rsocket
9.3.1. A Request/Response Example
9.3.2. A Fire-and-Forget Example
9.3.3. A Streaming (Channel) Example
9.3.4. A Bidirectional Example
9.3.5. Metadata
9.4. Bootiful RSocket
9.4.1. Request/Response Example
9.4.2. A Streaming (Channel) Example
9.4.3. A Fire and Forget
9.4.4. Bidirectional Communication
9.4.5. Setup Connections
9.4.6. Routing
9.4.7. Encoding
9.4.8. Metadata
9.4.9. Error Handling
9.5. Security
9.6. Spring Integration
9.7. Next Steps
9.7.1. An RSocket Broker
9.7.2. A Declarative RSocket Client
9.7.3. A Super Handy RSocket CLI
Chapter 10. Service Orchestration and Composition
10.1. Service Registration and Discovery
10.2. Some Simple Sample Services
10.2.1. Customer Service
10.2.2. Order Service
10.2.3. Profile Service
10.2.4. Error Service
10.2.5. Slow Service
10.2.6. The Client
10.3. Client Side Loadbalancing in the WebClient
10.4. Resilient Streams with Reactor Operators
10.5. Resilient Streams with Resilience4J
10.5.1. Retries
10.5.2. Circuit Breakers
10.5.3. Rate Limiters
10.5.4. Bulkheads
10.6. Hedging
10.7. Reactive Scatter/Gather
10.8. API Gateways with Spring Cloud Gateway
10.8.1. A Microproxy
10.8.2. Predicates
10.8.3. Filters
10.8.4. Discovery and Routing
10.8.5. Events
10.8.6. Alternative Configuration
10.9. Summary
Chapter 11. Action!
11.1. Websites to Bookmark
11.2. Additional reading
Acknowledgements
Chapter 12. About the Author


## Cloud native spring
ch01: introduction cloud native
-	Các ứng dụng cloud native là các hệ thống phân tán cao được thiết kế đặc biệt và hoạt động trên đám mây.
-	Đám mây là một cơ sở hạ tầng CNTT được cung cấp dưới dạng hàng hóa về tài nguyên điện toán, lưu trữ và mạng
-	Trong đám mây, người dùng chỉ trả tiền cho các tài nguyên thực tế mà họ sử dụng.
-	Nền tảng đám mây cung cấp dịch vụ của họ ở các cấp độ trừu tượng khác nhau: cơ sở hạ tầng (IaaS), container (CaaS), nền tảng (PaaS), chức năng (FaaS) hoặc phần mềm (SaaS).
-	Các ứng dụng cloud native có khả năng mở rộng theo chiều ngang horizontally scalable, loosely coupled, highly cohesive, có khả năng phục hồi trước các lỗi resilient to faults, manageable và observable.
-	Cloud native development được hỗ trợ bởi tự động hóa, continuous delivery continuous delivery và DevOps
-	Continuous delivery là một thực hành kỹ thuật toàn diện để cung cấp phần mềm chất lượng cao một cách nhanh chóng, đáng tin cậy và an toàn.
-	DevOps là một nền văn hóa cho phép cộng tác giữa các vai trò khác nhau để cùng nhau mang lại giá trị kinh doanh.
-	Các doanh nghiệp hiện đại sử dụng cloud native để sản xuất phần mềm có thể được phân phối nhanh chóng, có thể được mở rộng linh hoạt tùy thuộc vào nhu cầu và luôn sẵn sàng và có khả năng phục hồi trước các thất bại trong khi tối ưu hóa chi phí
-	Các container (chẳng hạn như container Docker) có thể được sử dụng làm computational units khi thiết kế các hệ thống cloud native. Chúng nhẹ hơn máy ảo và cung cấp tính di động, bất biến và linh hoạt
-	Các nền tảng chuyên dụng (như Kubernetes) cung cấp các dịch vụ để quản lý các container mà không cần xử lý trực tiếp các lớp bên dưới. Họ cung cấp container orchestration, cluster management, network services, and scheduling.
-	Serverless là một mô hình trong đó nền tảng (chẳng hạn như Knative) quản lý các máy chủ và cơ sở hạ tầng cơ bản và nhà phát triển chỉ tập trung vào logic nghiệp vụ. Chức năng phụ trợ được bật trên cơ sở trả tiền cho mỗi lần sử dụng để tối ưu hóa chi phí
-	Kiến trúc microservices có thể được sử dụng để xây dựng các ứng dụng cloud native, nhưng đó không phải là một yêu cầu.
-	Để thiết kế các ứng dụng cloud native, chúng tôi sẽ sử dụng service-based style architecture được đặc trưng bởi các dịch vụ và tương tác của chúng.
-	Cloud native services có thể được phân loại thành application services (stateless) and data services (stateful).

ch02: Cloud native patterns and technologies
-	Phương pháp 15 yếu tố xác định các nguyên tắc phát triển để xây dựng các ứng dụng cung cấp tính di động tối đa trên các môi trường thực thi, phù hợp để triển khai trên nền tảng đám mây, có thể được mở rộng, đảm bảo sự cân bằng môi trường giữa phát triển và sản xuất và cho phép continuous delivery.
-	Spring là một bộ các dự án cung cấp tất cả các chức năng phổ biến nhất để xây dựng các ứng dụng hiện đại trong Java.
-	Spring Framework cung cấp một application context trong đó beans và properties được quản lý trong toàn bộ vòng đời
-	Spring Boot đặt nền tảng cho phát triển cloud native bằng cách tăng tốc độ xây dựng các ứng dụng sẵn sàng sản xuất, bao gồm các máy chủ nhúng, tự động cấu hình, giám sát và các tính năng containerization.
-	Container images là các lightweight executable packages bao gồm mọi thứ cần thiết để chạy các ứng dụng bên trong.
-	Docker là một nền tảng tuân thủ OCI để xây dựng và chạy các container.
-	Một ứng dụng Spring Boot có thể được đóng gói dưới dạng container image với Cloud Native Buildpacks, một dự án CNCF chỉ định cách chuyển đổi mã nguồn ứng dụng thành container image sẵn sàng sản xuất
-	Khi xử lý một số container, như thường thấy trong hệ thống cloud native, bạn cần quản lý hệ thống phức tạp này. Kubernetes cung cấp chức năng điều phối orchestrate, schedule và manage containers
-	Kubernetes Pod là đơn vị triển khai tối thiểu.
-	Kubernetes Deployments mô tả cách tạo các phiên bản ứng dụng dưới dạng Pod, bắt đầu từ container images.
-	Kubernetes Services cho phép bạn expose các endpoints của ứng dụng ra bên ngoài cụm.

ch03: Getting started with cloud native development
-	Mỗi ứng dụng cloud native nên được theo dõi trong codebase riêng của nó và tất cả các phụ thuộc của nó phải được khai báo trong một tệp kê khai bằng các công cụ như Gradle hoặc Maven.
-	Các ứng dụng cloud native không phụ thuộc vào các máy chủ được đưa vào môi trường. Thay vào đó, chúng sử dụng một máy chủ nhúng và khép kín.
-	Tomcat là máy chủ nhúng mặc định cho các ứng dụng Spring Boot, và nó có thể được cấu hình thông qua các thuộc tính để tùy chỉnh các cổng mà nó lắng nghe, kết nối, hết thời gian chờ và luồng.
-	Tương tác request/response được cung cấp bởi một container Servlet như Tomcat vừa đồng bộ vừa chặn. Mỗi luồng xử lý một yêu cầu HTTP cho đến khi phản hồi được trả về.
-	Nguyên tắc đầu tiên của API khuyến nghị thiết kế API trước khi triển khai logic nghiệp vụ để thiết lập hợp đồng. Bằng cách này, các nhóm khác có thể phát triển dịch vụ của họ để sử dụng ứng dụng của bạn dựa trên chính hợp đồng mà không cần đợi ứng dụng kết thúc.
-	Trong Spring MVC, REST API được triển khai trong các lớp @RestController
-	Mỗi REST controller method xử lý một request đến với một phương thức cụ thể (GET, POST, PUT, DELETE) và điểm cuối (ví dụ: /books).
-	Các controller method có thể khai báo endpoint và hoạt động nào chúng xử lý thông qua các chú thích @GetMapping, @PostMapping, @PutMapping, @DeleteMapping và @RequestMapping.
-	Các phương thức của một lớp @RestController có thể validate HTTP request body trước khi quá trình xử lý xảy ra bằng cách áp dụng chú thích @Valid.
-	Các validation constraints cho một đối tượng Java nhất định được xác định bằng cách sử dụng các chú thích từ Java Bean Validation API trên các trường (ví dụ: @NotBlank, @Pattern, @Positive).
-	Các ngoại lệ Java được ném trong quá trình xử lý yêu cầu HTTP có thể được ánh xạ tới mã trạng thái HTTP và phần thân trong lớp @RestControllerAdvice tập trung, tách xử lý ngoại lệ cho API REST khỏi mã ném ngoại lệ.
-	Các unit test không biết cấu hình Spring nhưng có thể được viết dưới dạng các bài kiểm tra Java tiêu chuẩn bằng các công cụ quen thuộc như JUnit, Mockito và AssertJ.
-	Integration test cần một Spring application context để chạy. Một application context đầy đủ, bao gồm một máy chủ nhúng tùy chọn, có thể được khởi tạo để kiểm tra bằng cách sử dụng chú thích @SpringBootTest.
-	Khi các bài kiểm thử chỉ tập trung vào một "lát cắt" của ứng dụng và chỉ cần một phần cấu hình, Spring Boot cung cấp một số chú thích cho các bài kiểm thử tích hợp được nhắm mục tiêu hơn. Khi bạn sử dụng các annotation đó, một Spring application context được khởi tạo, nhưng chỉ có các component và phần cấu hình được sử dụng bởi lát chức năng cụ thể mới được load
-	@WebMvcTest là để test các MVC components của Spring.
-	@JsonTest là để test JSON serialization và deserialization.
-	GitHub Actions là một công cụ được cung cấp bởi GitHub để khai báo pipelines (hoặc workflows) để tự động hóa các tác vụ. Nó có thể được sử dụng để xây dựng một deployment pipeline.

ch04: Externalized configuration management
-	Sự trừu tượng của Spring Environment cung cấp một giao diện thống nhất để truy cập các properties và profiles.
-	Properties là các cặp key/value được sử dụng để lưu trữ cấu hình
-	Profile là các nhóm bean logic chỉ được đăng ký khi một profile cụ thể đang hoạt động.
-	Spring Boot thu thập các thuộc tính từ các nguồn khác nhau theo các quy tắc ưu tiên. Từ ưu tiên cao nhất đến thấp nhất, các thuộc tính có thể được xác định trong các đối số dòng lệnh, biến hệ thống JVM, biến môi trường hệ điều hành, tệp thuộc tính dành riêng cho hồ sơ và tệp thuộc tính chung
-	Spring beans có thể truy cập các thuộc tính từ đối tượng Environment bằng cách inject value với chú thích @Value hoặc từ một bean được ánh xạ đến một tập hợp các thuộc tính với chú thích @ConfigurationProperties.
-	Các active profiles có thể được định nghĩa với thuộc tính spring.profiles.active.
-	Chú thích @Profile đánh dấu các beans hoặc các configuration classes chỉ được xem xét khi profile được chỉ định đang hoạt động.
-	Properties, như được quản lý trong Spring Boot, cung cấp cấu hình bên ngoài như được xác định bởi phương pháp 15-Factor, nhưng điều đó là không đủ.
-	Một configuration server xử lý các khía cạnh như secret encryption, truy xuất nguồn gốc cấu hình configuration traceability, versioning và làm mới context trong thời gian chạy mà không cần khởi động lại.
-	Một config server có thể được thiết lập với thư viện Spring Cloud Config Server.
-	Bản thân cấu hình có thể được lưu trữ theo các chiến lược khác nhau, chẳng hạn như trong Git repository chuyên dụng.
-	Config server sử dụng application name, active profiles và Git-specific labels để xác định cấu hình nào sẽ được cung cấp cho ứng dụng nào.
-	Một ứng dụng Spring Boot có thể được cấu hình thông qua một config server sử dụng thư viện Spring Cloud Config Client.
-	@ConfigurationProperties đậu được cấu hình để nghe các sự kiện RefreshScopeRefreshedEvent.
-	Các sự kiện RefreshScopeRefreshedEvent có thể được kích hoạt sau khi một thay đổi mới được đẩy vào kho lưu trữ cấu hình, để ứng dụng khách tải lại ngữ cảnh bằng cách sử dụng dữ liệu cấu hình mới nhất.
-	Spring Boot Actuator định nghĩa một /actuator/refresh endpoint mà các bạn có thể sử dụng để trigger event theo cách thủ công.

ch05: Persisting and managing data in the cloud
-	Trạng thái là tất cả mọi thứ cần được bảo tồn khi tắt một dịch vụ và quay vòng một phiên bản mới.
-	Data services là các thành phần trạng thái của kiến trúc cloud native, đòi hỏi các công nghệ lưu trữ phải duy trì trạng thái
-	Sử dụng các dịch vụ dữ liệu trên đám mây là một thách thức vì đó là một môi trường năng động.
-	Một số vấn đề cần xem xét khi lựa chọn dịch vụ dữ liệu là khả năng mở rộng, khả năng phục hồi, hiệu suất và tuân thủ các quy định và luật pháp cụ thể.
-	Bạn có thể sử dụng các dịch vụ dữ liệu được cung cấp và quản lý bởi nhà cung cấp đám mây của bạn hoặc quản lý của riêng bạn, dựa vào các máy ảo hoặc vùng chứa.
-	Spring Data cung cấp các trừu tượng và pattern phổ biến để truy cập dữ liệu, giúp dễ dàng điều hướng các mô-đun khác nhau dành riêng cho cơ sở dữ liệu quan hệ và phi quan hệ.
-	Các yếu tố chính trong Spring Data là database drivers, entities và repositories.
-	Spring Data JDBC là một framework hỗ trợ tích hợp các ứng dụng Spring với các cơ sở dữ liệu quan hệ dựa trên một trình JDBC driver.
-	Các thực thể đại diện cho các đối tượng domain và có thể được quản lý bởi Spring Data JDBC dưới dạng các đối tượng bất biến. Họ phải có trường lưu trữ khóa chính được chú thích bằng @Id.
-	Spring Data cho phép bạn nắm bắt metadata auditing bất cứ khi nào một thực thể được tạo hoặc cập nhật. Bạn có thể bật tính năng này bằng @EnableJdbcAuditing.
-	Data repositories cấp quyền truy cập cho các thực thể từ cơ sở dữ liệu. Bạn cần định nghĩa một interface, và sau đó Spring Data sẽ tạo ra việc triển khai cho bạn.
-	Tùy thuộc vào yêu cầu của bạn, bạn có thể mở rộng một trong các giao diện Repository có sẵn được cung cấp bởi Spring Data, chẳng hạn như CrudRepository.
-	Trong Spring Data JDBC, tất cả các hoạt động mutating tùy chỉnh (create, update, delete) sẽ chạy trong các transaction.
-	Sử dụng chú thích @Transactional để chạy các hoạt động trong một unit of work.
-	Bạn có thể chạy integration test cho Spring Data JDBC slice bằng cách sử dụng annotation @DataJdbcTest.
-	Environment parity là điều cần thiết cho chất lượng và độ tin cậy của tests và deployment pipeline của bạn.
-	Bạn có thể test integration giữa ứng dụng của bạn và các backing services được xác định là container bằng cách sử dụng thư viện Testcontainers. Thư viện này cho phép bạn sử dụng các container nhẹ, có thể bỏ đi sau khi sử dụng trong các bài kiểm tra tích hợp của bạn.
-	Lược đồ cơ sở dữ liệu rất quan trọng đối với các ứng dụng. Trong sản xuất, bạn nên sử dụng một công cụ như Flyway, cung cấp kiểm soát phiên bản cho cơ sở dữ liệu của bạn.
-	Flyway nên quản lý bất kỳ thay đổi cơ sở dữ liệu nào để đảm bảo khả năng tái tạo, truy xuất nguồn gốc và độ tin cậy







