# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.456 ops/ms
# Warmup Iteration   2: 9.091 ops/ms
# Warmup Iteration   3: 10.127 ops/ms
Iteration   1: 10.555 ops/ms
Iteration   2: 10.159 ops/ms
Iteration   3: 9.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.222 ±(99.9%) 5.579 ops/ms [Average]
  (min, avg, max) = (9.953, 10.222, 10.555), stdev = 0.306
  CI (99.9%): [4.643, 15.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.769 ops/ms
# Warmup Iteration   2: 10.132 ops/ms
# Warmup Iteration   3: 10.508 ops/ms
Iteration   1: 10.837 ops/ms
Iteration   2: 10.510 ops/ms
Iteration   3: 10.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.703 ±(99.9%) 3.125 ops/ms [Average]
  (min, avg, max) = (10.510, 10.703, 10.837), stdev = 0.171
  CI (99.9%): [7.578, 13.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.330 ops/ms
# Warmup Iteration   2: 9.869 ops/ms
# Warmup Iteration   3: 10.153 ops/ms
Iteration   1: 10.128 ops/ms
Iteration   2: 10.169 ops/ms
Iteration   3: 9.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.097 ±(99.9%) 1.655 ops/ms [Average]
  (min, avg, max) = (9.995, 10.097, 10.169), stdev = 0.091
  CI (99.9%): [8.443, 11.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.489 ops/ms
# Warmup Iteration   2: 7.517 ops/ms
# Warmup Iteration   3: 7.785 ops/ms
Iteration   1: 7.754 ops/ms
Iteration   2: 7.763 ops/ms
Iteration   3: 7.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.757 ±(99.9%) 0.101 ops/ms [Average]
  (min, avg, max) = (7.753, 7.757, 7.763), stdev = 0.006
  CI (99.9%): [7.655, 7.858] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.264 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.012 ms/op
Iteration   1: 3.188 ±(99.9%) 0.001 ms/op
Iteration   2: 3.204 ±(99.9%) 0.002 ms/op
Iteration   3: 3.179 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.190 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (3.179, 3.190, 3.204), stdev = 0.013
  CI (99.9%): [2.962, 3.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.073 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.002 ms/op
Iteration   1: 2.979 ±(99.9%) 0.002 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 3.014 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.993 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (2.979, 2.993, 3.014), stdev = 0.019
  CI (99.9%): [2.654, 3.332] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.454 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.002 ms/op
Iteration   1: 3.146 ±(99.9%) 0.004 ms/op
Iteration   2: 3.122 ±(99.9%) 0.003 ms/op
Iteration   3: 3.146 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.138 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (3.122, 3.138, 3.146), stdev = 0.014
  CI (99.9%): [2.886, 3.390] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.380 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.014 ms/op
Iteration   1: 4.054 ±(99.9%) 0.018 ms/op
Iteration   2: 4.087 ±(99.9%) 0.007 ms/op
Iteration   3: 4.001 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.048 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (4.001, 4.048, 4.087), stdev = 0.044
  CI (99.9%): [3.253, 4.842] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.144 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.006 ms/op
Iteration   1: 3.164 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.090 ms/op
                 createUser·p0.9999: 14.938 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   2: 3.207 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.372 ms/op
                 createUser·p0.999:  6.408 ms/op
                 createUser·p0.9999: 21.890 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  10.712 ms/op
                 createUser·p0.9999: 27.587 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301970
  mean =      3.180 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23812 
    [ 2.500,  5.000) = 277151 
    [ 5.000,  7.500) = 646 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.086 ms/op
     p(99.9900) =     26.909 ms/op
     p(99.9990) =     27.852 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
Iteration   1: 3.089 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.906 ms/op
                 existUser·p0.9999: 13.443 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.328 ms/op
                 existUser·p0.9999: 15.681 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   3: 2.978 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.597 ms/op
                 existUser·p0.9999: 29.917 ms/op
                 existUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315648
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43795 
    [ 2.500,  5.000) = 270733 
    [ 5.000,  7.500) = 770 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.720 ms/op
     p(99.9900) =     24.689 ms/op
     p(99.9990) =     30.109 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.531 ms/op
                 getUser·p0.9999: 16.753 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.111 ms/op
                 getUser·p0.9999: 21.013 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   3: 3.224 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  8.873 ms/op
                 getUser·p0.9999: 20.911 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303306
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19735 
    [ 2.500,  5.000) = 282586 
    [ 5.000,  7.500) = 720 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.274 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     21.593 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.100 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.011 ms/op
Iteration   1: 4.038 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  17.655 ms/op
                 listUser·p0.9999: 20.712 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 4.046 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.007 ms/op
                 listUser·p0.9999: 23.105 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 4.101 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  18.806 ms/op
                 listUser·p0.9999: 27.413 ms/op
                 listUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236296
  mean =      4.061 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1932 
    [ 2.500,  5.000) = 208489 
    [ 5.000,  7.500) = 24784 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     16.964 ms/op
     p(99.9900) =     25.080 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.222 ± 5.579  ops/ms
ClientGrpc.existUser                       thrpt       3  10.703 ± 3.125  ops/ms
ClientGrpc.getUser                         thrpt       3  10.097 ± 1.655  ops/ms
ClientGrpc.listUser                        thrpt       3   7.757 ± 0.101  ops/ms
ClientGrpc.createUser                       avgt       3   3.190 ± 0.229   ms/op
ClientGrpc.existUser                        avgt       3   2.993 ± 0.339   ms/op
ClientGrpc.getUser                          avgt       3   3.138 ± 0.252   ms/op
ClientGrpc.listUser                         avgt       3   4.048 ± 0.794   ms/op
ClientGrpc.createUser                     sample  301970   3.180 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.656           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.086           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.909           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.049           ms/op
ClientGrpc.existUser                      sample  315648   3.041 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.550           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.720           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.689           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.147           ms/op
ClientGrpc.getUser                        sample  303306   3.165 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.713           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.274           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.840           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.594           ms/op
ClientGrpc.listUser                       sample  236296   4.061 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.901           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.964           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.080           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
