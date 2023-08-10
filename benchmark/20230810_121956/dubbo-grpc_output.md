# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.074 ops/ms
# Warmup Iteration   2: 6.829 ops/ms
# Warmup Iteration   3: 8.429 ops/ms
Iteration   1: 8.962 ops/ms
Iteration   2: 9.141 ops/ms
Iteration   3: 9.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.134 ±(99.9%) 3.076 ops/ms [Average]
  (min, avg, max) = (8.962, 9.134, 9.299), stdev = 0.169
  CI (99.9%): [6.059, 12.210] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.086 ops/ms
# Warmup Iteration   2: 8.890 ops/ms
# Warmup Iteration   3: 9.376 ops/ms
Iteration   1: 9.752 ops/ms
Iteration   2: 9.486 ops/ms
Iteration   3: 9.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.628 ±(99.9%) 2.448 ops/ms [Average]
  (min, avg, max) = (9.486, 9.628, 9.752), stdev = 0.134
  CI (99.9%): [7.180, 12.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.820 ops/ms
# Warmup Iteration   2: 8.538 ops/ms
# Warmup Iteration   3: 9.020 ops/ms
Iteration   1: 8.971 ops/ms
Iteration   2: 9.282 ops/ms
Iteration   3: 9.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.194 ±(99.9%) 3.564 ops/ms [Average]
  (min, avg, max) = (8.971, 9.194, 9.331), stdev = 0.195
  CI (99.9%): [5.631, 12.758] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.452 ops/ms
# Warmup Iteration   2: 6.672 ops/ms
# Warmup Iteration   3: 6.935 ops/ms
Iteration   1: 6.927 ops/ms
Iteration   2: 7.131 ops/ms
Iteration   3: 7.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.055 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (6.927, 7.055, 7.131), stdev = 0.112
  CI (99.9%): [5.017, 9.094] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.029 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.003 ms/op
Iteration   1: 3.514 ±(99.9%) 0.003 ms/op
Iteration   2: 3.708 ±(99.9%) 0.003 ms/op
Iteration   3: 3.477 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.567 ±(99.9%) 2.265 ms/op [Average]
  (min, avg, max) = (3.477, 3.567, 3.708), stdev = 0.124
  CI (99.9%): [1.301, 5.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.587 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.004 ms/op
Iteration   1: 3.322 ±(99.9%) 0.003 ms/op
Iteration   2: 3.315 ±(99.9%) 0.004 ms/op
Iteration   3: 3.304 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.314 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (3.304, 3.314, 3.322), stdev = 0.009
  CI (99.9%): [3.150, 3.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.064 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.004 ms/op
Iteration   1: 3.541 ±(99.9%) 0.003 ms/op
Iteration   2: 3.497 ±(99.9%) 0.003 ms/op
Iteration   3: 3.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.515 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.497, 3.515, 3.541), stdev = 0.023
  CI (99.9%): [3.092, 3.938] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.522 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.831 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.680 ±(99.9%) 0.012 ms/op
Iteration   1: 4.628 ±(99.9%) 0.010 ms/op
Iteration   2: 4.512 ±(99.9%) 0.010 ms/op
Iteration   3: 4.574 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.571 ±(99.9%) 1.056 ms/op [Average]
  (min, avg, max) = (4.512, 4.571, 4.628), stdev = 0.058
  CI (99.9%): [3.515, 5.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.159 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.009 ms/op
Iteration   1: 3.559 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  11.110 ms/op
                 createUser·p0.9999: 15.139 ms/op
                 createUser·p1.00:   15.892 ms/op

Iteration   2: 3.569 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.494 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  12.999 ms/op
                 createUser·p0.9999: 16.781 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   3: 3.572 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 19.171 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 269047
  mean =      3.567 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 8554 
    [ 2.500,  3.750) = 177545 
    [ 3.750,  5.000) = 76194 
    [ 5.000,  6.250) = 4640 
    [ 6.250,  7.500) = 835 
    [ 7.500,  8.750) = 572 
    [ 8.750, 10.000) = 215 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 87 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     11.057 ms/op
     p(99.9900) =     18.520 ms/op
     p(99.9990) =     19.429 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.014 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.008 ms/op
Iteration   1: 3.368 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  8.256 ms/op
                 existUser·p0.9999: 13.729 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   2: 3.422 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.542 ms/op
                 existUser·p0.999:  8.237 ms/op
                 existUser·p0.9999: 16.072 ms/op
                 existUser·p1.00:   16.564 ms/op

Iteration   3: 3.448 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  11.817 ms/op
                 existUser·p0.9999: 23.584 ms/op
                 existUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281409
  mean =      3.412 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12548 
    [ 2.500,  5.000) = 264236 
    [ 5.000,  7.500) = 4020 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     23.769 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.128 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.009 ms/op
Iteration   1: 3.531 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  11.839 ms/op
                 getUser·p0.9999: 15.008 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   2: 3.514 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 25.818 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   3: 3.511 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  10.076 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 272971
  mean =      3.519 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11812 
    [ 2.500,  5.000) = 254501 
    [ 5.000,  7.500) = 5777 
    [ 7.500, 10.000) = 534 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     10.978 ms/op
     p(99.9900) =     25.385 ms/op
     p(99.9990) =     26.059 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.920 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.926 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.602 ±(99.9%) 0.014 ms/op
Iteration   1: 4.609 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  16.060 ms/op
                 listUser·p0.9999: 18.352 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 4.705 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   6.840 ms/op
                 listUser·p0.99:   8.883 ms/op
                 listUser·p0.999:  16.139 ms/op
                 listUser·p0.9999: 20.061 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 4.689 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  20.408 ms/op
                 listUser·p0.9999: 29.032 ms/op
                 listUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205588
  mean =      4.667 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 592 
    [ 2.500,  5.000) = 158099 
    [ 5.000,  7.500) = 41478 
    [ 7.500, 10.000) = 4478 
    [10.000, 12.500) = 541 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =      6.808 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     27.789 ms/op
     p(99.9990) =     29.191 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.134 ± 3.076  ops/ms
ClientGrpc.existUser                       thrpt       3   9.628 ± 2.448  ops/ms
ClientGrpc.getUser                         thrpt       3   9.194 ± 3.564  ops/ms
ClientGrpc.listUser                        thrpt       3   7.055 ± 2.038  ops/ms
ClientGrpc.createUser                       avgt       3   3.567 ± 2.265   ms/op
ClientGrpc.existUser                        avgt       3   3.314 ± 0.164   ms/op
ClientGrpc.getUser                          avgt       3   3.515 ± 0.423   ms/op
ClientGrpc.listUser                         avgt       3   4.571 ± 1.056   ms/op
ClientGrpc.createUser                     sample  269047   3.567 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.768           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.057           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.520           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.530           ms/op
ClientGrpc.existUser                      sample  281409   3.412 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.439           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.421           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.480           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.855           ms/op
ClientGrpc.getUser                        sample  272971   3.519 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.672           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.978           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.385           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.116           ms/op
ClientGrpc.listUser                       sample  205588   4.667 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.432           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.798           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.482           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.789           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.295           ms/op
