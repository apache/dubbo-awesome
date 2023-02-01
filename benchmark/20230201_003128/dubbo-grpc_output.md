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
# Warmup Iteration   1: 2.206 ops/ms
# Warmup Iteration   2: 6.075 ops/ms
# Warmup Iteration   3: 7.278 ops/ms
Iteration   1: 7.238 ops/ms
Iteration   2: 7.202 ops/ms
Iteration   3: 7.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.185 ±(99.9%) 1.157 ops/ms [Average]
  (min, avg, max) = (7.114, 7.185, 7.238), stdev = 0.063
  CI (99.9%): [6.028, 8.342] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ops/ms
# Warmup Iteration   2: 7.362 ops/ms
# Warmup Iteration   3: 7.368 ops/ms
Iteration   1: 7.463 ops/ms
Iteration   2: 7.543 ops/ms
Iteration   3: 7.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.581 ±(99.9%) 2.574 ops/ms [Average]
  (min, avg, max) = (7.463, 7.581, 7.737), stdev = 0.141
  CI (99.9%): [5.007, 10.154] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.600 ops/ms
# Warmup Iteration   2: 6.828 ops/ms
# Warmup Iteration   3: 7.153 ops/ms
Iteration   1: 7.367 ops/ms
Iteration   2: 7.206 ops/ms
Iteration   3: 7.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.429 ±(99.9%) 4.726 ops/ms [Average]
  (min, avg, max) = (7.206, 7.429, 7.713), stdev = 0.259
  CI (99.9%): [2.702, 12.155] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ops/ms
# Warmup Iteration   2: 5.142 ops/ms
# Warmup Iteration   3: 5.632 ops/ms
Iteration   1: 5.770 ops/ms
Iteration   2: 5.927 ops/ms
Iteration   3: 5.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.885 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (5.770, 5.885, 5.959), stdev = 0.101
  CI (99.9%): [4.043, 7.727] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.448 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.636 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.395 ±(99.9%) 0.021 ms/op
Iteration   1: 4.419 ±(99.9%) 0.004 ms/op
Iteration   2: 4.318 ±(99.9%) 0.003 ms/op
Iteration   3: 4.404 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.381 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (4.318, 4.381, 4.419), stdev = 0.054
  CI (99.9%): [3.387, 5.374] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.192 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.003 ms/op
Iteration   1: 4.273 ±(99.9%) 0.004 ms/op
Iteration   2: 4.172 ±(99.9%) 0.003 ms/op
Iteration   3: 4.260 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.235 ±(99.9%) 0.997 ms/op [Average]
  (min, avg, max) = (4.172, 4.235, 4.273), stdev = 0.055
  CI (99.9%): [3.237, 5.232] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.594 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.542 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.354 ±(99.9%) 0.016 ms/op
Iteration   1: 4.429 ±(99.9%) 0.003 ms/op
Iteration   2: 4.349 ±(99.9%) 0.007 ms/op
Iteration   3: 4.537 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.438 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (4.349, 4.438, 4.537), stdev = 0.094
  CI (99.9%): [2.717, 6.159] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.576 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.614 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.616 ±(99.9%) 0.012 ms/op
Iteration   1: 5.329 ±(99.9%) 0.013 ms/op
Iteration   2: 5.344 ±(99.9%) 0.013 ms/op
Iteration   3: 5.240 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.304 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (5.240, 5.304, 5.344), stdev = 0.056
  CI (99.9%): [4.287, 6.322] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.154 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.744 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.509 ±(99.9%) 0.012 ms/op
Iteration   1: 4.326 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   4.252 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  10.655 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   2: 4.114 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   5.358 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  10.409 ms/op
                 createUser·p0.9999: 19.610 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   3: 4.040 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  11.452 ms/op
                 createUser·p0.9999: 20.843 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 230780
  mean =      4.157 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7049 
    [ 2.500,  5.000) = 185897 
    [ 5.000,  7.500) = 36488 
    [ 7.500, 10.000) = 1035 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     10.883 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     21.155 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 6.164 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.010 ms/op
Iteration   1: 4.042 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   8.077 ms/op
                 existUser·p0.999:  11.647 ms/op
                 existUser·p0.9999: 31.457 ms/op
                 existUser·p1.00:   32.604 ms/op

Iteration   2: 3.588 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.093 ms/op
                 existUser·p0.999:  9.662 ms/op
                 existUser·p0.9999: 17.441 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   3: 3.840 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   6.110 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 17.379 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 251447
  mean =      3.814 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11749 
    [ 2.500,  5.000) = 217222 
    [ 5.000,  7.500) = 20807 
    [ 7.500, 10.000) = 1208 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     11.370 ms/op
     p(99.9900) =     29.275 ms/op
     p(99.9990) =     32.042 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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
# Warmup Iteration   1: 5.745 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.011 ms/op
Iteration   1: 3.862 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  9.283 ms/op
                 getUser·p0.9999: 23.205 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.782 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  10.901 ms/op
                 getUser·p0.9999: 18.287 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   3: 3.760 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  11.920 ms/op
                 getUser·p0.9999: 20.856 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252696
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6407 
    [ 2.500,  5.000) = 228603 
    [ 5.000,  7.500) = 16849 
    [ 7.500, 10.000) = 579 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     10.309 ms/op
     p(99.9900) =     22.494 ms/op
     p(99.9990) =     23.653 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.427 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.257 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.084 ±(99.9%) 0.018 ms/op
Iteration   1: 5.188 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  15.953 ms/op
                 listUser·p0.9999: 18.994 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 4.989 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   6.562 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  15.623 ms/op
                 listUser·p0.9999: 29.871 ms/op
                 listUser·p1.00:   30.343 ms/op

Iteration   3: 4.935 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 27.132 ms/op
                 listUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 190839
  mean =      5.035 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 370 
    [ 2.500,  5.000) = 112608 
    [ 5.000,  7.500) = 68359 
    [ 7.500, 10.000) = 8061 
    [10.000, 12.500) = 928 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =      9.535 ms/op
     p(99.9000) =     16.490 ms/op
     p(99.9900) =     28.601 ms/op
     p(99.9990) =     30.313 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.185 ± 1.157  ops/ms
ClientGrpc.existUser                       thrpt       3   7.581 ± 2.574  ops/ms
ClientGrpc.getUser                         thrpt       3   7.429 ± 4.726  ops/ms
ClientGrpc.listUser                        thrpt       3   5.885 ± 1.842  ops/ms
ClientGrpc.createUser                       avgt       3   4.381 ± 0.994   ms/op
ClientGrpc.existUser                        avgt       3   4.235 ± 0.997   ms/op
ClientGrpc.getUser                          avgt       3   4.438 ± 1.721   ms/op
ClientGrpc.listUser                         avgt       3   5.304 ± 1.018   ms/op
ClientGrpc.createUser                     sample  230780   4.157 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.876           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.374           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.849           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.883           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.430           ms/op
ClientGrpc.existUser                      sample  251447   3.814 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.932           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.358           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.914           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.370           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.275           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.604           ms/op
ClientGrpc.getUser                        sample  252696   3.801 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.815           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.111           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.309           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.494           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  190839   5.035 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.350           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.496           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.535           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.490           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.601           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.343           ms/op
