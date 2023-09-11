# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.457 ops/ms
# Warmup Iteration   2: 5.176 ops/ms
# Warmup Iteration   3: 8.834 ops/ms
Iteration   1: 9.735 ops/ms
Iteration   2: 9.861 ops/ms
Iteration   3: 9.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.766 ±(99.9%) 1.532 ops/ms [Average]
  (min, avg, max) = (9.701, 9.766, 9.861), stdev = 0.084
  CI (99.9%): [8.234, 11.297] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.258 ops/ms
# Warmup Iteration   2: 9.301 ops/ms
# Warmup Iteration   3: 9.566 ops/ms
Iteration   1: 10.219 ops/ms
Iteration   2: 9.995 ops/ms
Iteration   3: 9.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.044 ±(99.9%) 2.855 ops/ms [Average]
  (min, avg, max) = (9.918, 10.044, 10.219), stdev = 0.157
  CI (99.9%): [7.189, 12.900] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.093 ops/ms
# Warmup Iteration   2: 8.629 ops/ms
# Warmup Iteration   3: 9.646 ops/ms
Iteration   1: 9.745 ops/ms
Iteration   2: 9.459 ops/ms
Iteration   3: 9.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.664 ±(99.9%) 3.269 ops/ms [Average]
  (min, avg, max) = (9.459, 9.664, 9.789), stdev = 0.179
  CI (99.9%): [6.395, 12.933] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.892 ops/ms
# Warmup Iteration   2: 7.111 ops/ms
# Warmup Iteration   3: 8.188 ops/ms
Iteration   1: 8.076 ops/ms
Iteration   2: 8.359 ops/ms
Iteration   3: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.292 ±(99.9%) 3.500 ops/ms [Average]
  (min, avg, max) = (8.076, 8.292, 8.442), stdev = 0.192
  CI (99.9%): [4.792, 11.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.215 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.003 ms/op
Iteration   1: 3.207 ±(99.9%) 0.004 ms/op
Iteration   2: 3.239 ±(99.9%) 0.006 ms/op
Iteration   3: 3.290 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.245 ±(99.9%) 0.766 ms/op [Average]
  (min, avg, max) = (3.207, 3.245, 3.290), stdev = 0.042
  CI (99.9%): [2.479, 4.011] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.592 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.005 ms/op
Iteration   1: 3.203 ±(99.9%) 0.006 ms/op
Iteration   2: 3.178 ±(99.9%) 0.002 ms/op
Iteration   3: 3.155 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.179 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (3.155, 3.179, 3.203), stdev = 0.024
  CI (99.9%): [2.737, 3.621] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.078 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.003 ms/op
Iteration   1: 3.455 ±(99.9%) 0.005 ms/op
Iteration   2: 3.371 ±(99.9%) 0.005 ms/op
Iteration   3: 3.235 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.354 ±(99.9%) 2.021 ms/op [Average]
  (min, avg, max) = (3.235, 3.354, 3.455), stdev = 0.111
  CI (99.9%): [1.333, 5.374] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.818 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.006 ms/op
Iteration   1: 3.929 ±(99.9%) 0.007 ms/op
Iteration   2: 3.929 ±(99.9%) 0.007 ms/op
Iteration   3: 3.859 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.906 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (3.859, 3.906, 3.929), stdev = 0.041
  CI (99.9%): [3.166, 4.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.613 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.010 ms/op
Iteration   1: 3.396 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  18.509 ms/op
                 createUser·p0.9999: 21.665 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.295 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  18.860 ms/op
                 createUser·p0.9999: 23.986 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 3.304 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  16.891 ms/op
                 createUser·p0.9999: 27.688 ms/op
                 createUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287967
  mean =      3.331 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18830 
    [ 2.500,  5.000) = 260682 
    [ 5.000,  7.500) = 6882 
    [ 7.500, 10.000) = 1080 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     17.204 ms/op
     p(99.9900) =     24.688 ms/op
     p(99.9990) =     28.588 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.854 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
Iteration   1: 3.151 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 19.706 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.230 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  14.181 ms/op
                 existUser·p0.9999: 23.405 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 3.248 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   6.657 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 28.196 ms/op
                 existUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299080
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16273 
    [ 2.500,  5.000) = 275643 
    [ 5.000,  7.500) = 5773 
    [ 7.500, 10.000) = 912 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     26.480 ms/op
     p(99.9990) =     28.772 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.532 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.009 ms/op
Iteration   1: 3.483 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   7.030 ms/op
                 getUser·p0.999:  13.224 ms/op
                 getUser·p0.9999: 21.702 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.242 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  9.811 ms/op
                 getUser·p0.9999: 25.563 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  10.599 ms/op
                 getUser·p0.9999: 23.233 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286317
  mean =      3.353 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11564 
    [ 2.500,  5.000) = 264492 
    [ 5.000,  7.500) = 8742 
    [ 7.500, 10.000) = 1123 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     12.529 ms/op
     p(99.9900) =     24.457 ms/op
     p(99.9990) =     25.914 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.636 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.014 ms/op
Iteration   1: 3.873 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.976 ms/op
                 listUser·p0.999:  16.499 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 3.791 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  13.271 ms/op
                 listUser·p0.9999: 14.615 ms/op
                 listUser·p1.00:   15.221 ms/op

Iteration   3: 3.782 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251503
  mean =      3.815 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 242626 
    [ 5.000,  7.500) = 6217 
    [ 7.500, 10.000) = 1820 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 323 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     19.992 ms/op
     p(99.9990) =     21.671 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.766 ± 1.532  ops/ms
ClientPb.existUser                       thrpt       3  10.044 ± 2.855  ops/ms
ClientPb.getUser                         thrpt       3   9.664 ± 3.269  ops/ms
ClientPb.listUser                        thrpt       3   8.292 ± 3.500  ops/ms
ClientPb.createUser                       avgt       3   3.245 ± 0.766   ms/op
ClientPb.existUser                        avgt       3   3.179 ± 0.442   ms/op
ClientPb.getUser                          avgt       3   3.354 ± 2.021   ms/op
ClientPb.listUser                         avgt       3   3.906 ± 0.739   ms/op
ClientPb.createUser                     sample  287967   3.331 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.321           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.997           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.204           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.688           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.360           ms/op
ClientPb.existUser                      sample  299080   3.209 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.185           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.828           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.480           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.967           ms/op
ClientPb.getUser                        sample  286317   3.353 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.529           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.457           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.149           ms/op
ClientPb.listUser                       sample  251503   3.815 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.610           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.553           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.697           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.992           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.889           ms/op
