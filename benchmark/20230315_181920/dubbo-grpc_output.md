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
# Warmup Iteration   1: 2.442 ops/ms
# Warmup Iteration   2: 5.542 ops/ms
# Warmup Iteration   3: 6.976 ops/ms
Iteration   1: 7.210 ops/ms
Iteration   2: 7.187 ops/ms
Iteration   3: 7.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.305 ±(99.9%) 3.386 ops/ms [Average]
  (min, avg, max) = (7.187, 7.305, 7.519), stdev = 0.186
  CI (99.9%): [3.920, 10.691] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.053 ops/ms
# Warmup Iteration   2: 7.357 ops/ms
# Warmup Iteration   3: 7.914 ops/ms
Iteration   1: 7.863 ops/ms
Iteration   2: 7.915 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.972 ±(99.9%) 2.678 ops/ms [Average]
  (min, avg, max) = (7.863, 7.972, 8.139), stdev = 0.147
  CI (99.9%): [5.294, 10.651] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.607 ops/ms
# Warmup Iteration   2: 6.933 ops/ms
# Warmup Iteration   3: 7.230 ops/ms
Iteration   1: 7.396 ops/ms
Iteration   2: 7.689 ops/ms
Iteration   3: 7.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.480 ±(99.9%) 3.330 ops/ms [Average]
  (min, avg, max) = (7.355, 7.480, 7.689), stdev = 0.183
  CI (99.9%): [4.150, 10.809] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.839 ops/ms
# Warmup Iteration   2: 5.243 ops/ms
# Warmup Iteration   3: 5.674 ops/ms
Iteration   1: 5.683 ops/ms
Iteration   2: 5.805 ops/ms
Iteration   3: 5.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.760 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (5.683, 5.760, 5.805), stdev = 0.067
  CI (99.9%): [4.534, 6.987] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.620 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.645 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.428 ±(99.9%) 0.007 ms/op
Iteration   1: 4.531 ±(99.9%) 0.004 ms/op
Iteration   2: 4.316 ±(99.9%) 0.002 ms/op
Iteration   3: 4.222 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.356 ±(99.9%) 2.891 ms/op [Average]
  (min, avg, max) = (4.222, 4.356, 4.531), stdev = 0.158
  CI (99.9%): [1.465, 7.248] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.288 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.301 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.004 ms/op
Iteration   1: 4.103 ±(99.9%) 0.002 ms/op
Iteration   2: 4.090 ±(99.9%) 0.002 ms/op
Iteration   3: 4.040 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.077 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (4.040, 4.077, 4.103), stdev = 0.033
  CI (99.9%): [3.472, 4.683] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.829 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.003 ms/op
Iteration   1: 4.299 ±(99.9%) 0.003 ms/op
Iteration   2: 4.276 ±(99.9%) 0.005 ms/op
Iteration   3: 4.206 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.260 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (4.206, 4.260, 4.299), stdev = 0.048
  CI (99.9%): [3.376, 5.144] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.921 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.982 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.514 ±(99.9%) 0.018 ms/op
Iteration   1: 5.562 ±(99.9%) 0.021 ms/op
Iteration   2: 5.435 ±(99.9%) 0.014 ms/op
Iteration   3: 5.511 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.503 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (5.435, 5.503, 5.562), stdev = 0.064
  CI (99.9%): [4.337, 6.668] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.411 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.498 ±(99.9%) 0.015 ms/op
Iteration   1: 4.358 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.667 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.612 ms/op
                 createUser·p0.95:   6.062 ms/op
                 createUser·p0.99:   7.835 ms/op
                 createUser·p0.999:  12.142 ms/op
                 createUser·p0.9999: 20.469 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   2: 4.365 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  14.379 ms/op
                 createUser·p0.9999: 26.325 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 4.352 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  16.181 ms/op
                 createUser·p0.9999: 27.787 ms/op
                 createUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220187
  mean =      4.358 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3178 
    [ 2.500,  5.000) = 170991 
    [ 5.000,  7.500) = 43773 
    [ 7.500, 10.000) = 1684 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     13.954 ms/op
     p(99.9900) =     27.162 ms/op
     p(99.9990) =     28.062 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.283 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.011 ms/op
Iteration   1: 4.063 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   3.953 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  10.916 ms/op
                 existUser·p0.9999: 18.129 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 3.929 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  12.116 ms/op
                 existUser·p0.9999: 33.030 ms/op
                 existUser·p1.00:   33.096 ms/op

Iteration   3: 3.949 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.946 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 18.147 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 241237
  mean =      3.979 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8045 
    [ 2.500,  5.000) = 208098 
    [ 5.000,  7.500) = 23357 
    [ 7.500, 10.000) = 1342 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     27.816 ms/op
     p(99.9990) =     33.096 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.125 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.639 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.013 ms/op
Iteration   1: 4.185 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  13.517 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 4.315 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   4.162 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.049 ms/op
                 getUser·p0.99:   8.125 ms/op
                 getUser·p0.999:  13.701 ms/op
                 getUser·p0.9999: 17.471 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   3: 4.254 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   8.053 ms/op
                 getUser·p0.999:  13.023 ms/op
                 getUser·p0.9999: 21.888 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225675
  mean =      4.251 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5971 
    [ 2.500,  5.000) = 184067 
    [ 5.000,  7.500) = 33078 
    [ 7.500, 10.000) = 1732 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     23.847 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.183 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.975 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.517 ±(99.9%) 0.021 ms/op
Iteration   1: 5.575 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   10.519 ms/op
                 listUser·p0.999:  14.957 ms/op
                 listUser·p0.9999: 20.456 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 5.585 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.141 ms/op
                 listUser·p0.999:  19.456 ms/op
                 listUser·p0.9999: 25.142 ms/op
                 listUser·p1.00:   30.212 ms/op

Iteration   3: 5.507 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   5.169 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  23.101 ms/op
                 listUser·p0.9999: 37.814 ms/op
                 listUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172739
  mean =      5.555 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 369 
    [ 2.500,  5.000) = 71368 
    [ 5.000,  7.500) = 82326 
    [ 7.500, 10.000) = 15629 
    [10.000, 12.500) = 2388 
    [12.500, 15.000) = 366 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     35.419 ms/op
     p(99.9990) =     38.636 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.305 ± 3.386  ops/ms
ClientGrpc.existUser                       thrpt       3   7.972 ± 2.678  ops/ms
ClientGrpc.getUser                         thrpt       3   7.480 ± 3.330  ops/ms
ClientGrpc.listUser                        thrpt       3   5.760 ± 1.227  ops/ms
ClientGrpc.createUser                       avgt       3   4.356 ± 2.891   ms/op
ClientGrpc.existUser                        avgt       3   4.077 ± 0.606   ms/op
ClientGrpc.getUser                          avgt       3   4.260 ± 0.884   ms/op
ClientGrpc.listUser                         avgt       3   5.503 ± 1.165   ms/op
ClientGrpc.createUser                     sample  220187   4.358 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.667           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.497           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.923           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.528           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.954           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.162           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.279           ms/op
ClientGrpc.existUser                      sample  241237   3.979 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.951           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.456           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.004           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.813           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.816           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.096           ms/op
ClientGrpc.getUser                        sample  225675   4.251 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.349           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.898           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.709           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.304           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.036           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  172739   5.555 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.139           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.619           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.846           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.645           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.419           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.732           ms/op
