# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.542 ops/ms
# Warmup Iteration   2: 3.255 ops/ms
# Warmup Iteration   3: 6.992 ops/ms
Iteration   1: 7.531 ops/ms
Iteration   2: 8.173 ops/ms
Iteration   3: 7.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.804 ±(99.9%) 6.050 ops/ms [Average]
  (min, avg, max) = (7.531, 7.804, 8.173), stdev = 0.332
  CI (99.9%): [1.754, 13.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.018 ops/ms
# Warmup Iteration   2: 6.114 ops/ms
# Warmup Iteration   3: 7.787 ops/ms
Iteration   1: 8.174 ops/ms
Iteration   2: 8.155 ops/ms
Iteration   3: 8.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.120 ±(99.9%) 1.421 ops/ms [Average]
  (min, avg, max) = (8.031, 8.120, 8.174), stdev = 0.078
  CI (99.9%): [6.699, 9.541] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.106 ops/ms
# Warmup Iteration   2: 5.671 ops/ms
# Warmup Iteration   3: 7.441 ops/ms
Iteration   1: 7.351 ops/ms
Iteration   2: 8.320 ops/ms
Iteration   3: 8.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.967 ±(99.9%) 9.761 ops/ms [Average]
  (min, avg, max) = (7.351, 7.967, 8.320), stdev = 0.535
  CI (99.9%): [≈ 0, 17.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.832 ops/ms
# Warmup Iteration   2: 5.072 ops/ms
# Warmup Iteration   3: 6.869 ops/ms
Iteration   1: 6.934 ops/ms
Iteration   2: 6.744 ops/ms
Iteration   3: 6.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.853 ±(99.9%) 1.793 ops/ms [Average]
  (min, avg, max) = (6.744, 6.853, 6.934), stdev = 0.098
  CI (99.9%): [5.060, 8.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.756 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.392 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.009 ms/op
Iteration   1: 4.041 ±(99.9%) 0.006 ms/op
Iteration   2: 3.965 ±(99.9%) 0.005 ms/op
Iteration   3: 3.965 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.990 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (3.965, 3.990, 4.041), stdev = 0.044
  CI (99.9%): [3.191, 4.790] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.651 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.242 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.007 ms/op
Iteration   1: 3.733 ±(99.9%) 0.010 ms/op
Iteration   2: 3.694 ±(99.9%) 0.010 ms/op
Iteration   3: 3.807 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.745 ±(99.9%) 1.047 ms/op [Average]
  (min, avg, max) = (3.694, 3.745, 3.807), stdev = 0.057
  CI (99.9%): [2.698, 4.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.922 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.010 ms/op
Iteration   1: 4.108 ±(99.9%) 0.004 ms/op
Iteration   2: 4.041 ±(99.9%) 0.007 ms/op
Iteration   3: 3.919 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.023 ±(99.9%) 1.749 ms/op [Average]
  (min, avg, max) = (3.919, 4.023, 4.108), stdev = 0.096
  CI (99.9%): [2.274, 5.771] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.202 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.708 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.047 ±(99.9%) 0.013 ms/op
Iteration   1: 4.745 ±(99.9%) 0.008 ms/op
Iteration   2: 4.617 ±(99.9%) 0.016 ms/op
Iteration   3: 4.552 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.638 ±(99.9%) 1.793 ms/op [Average]
  (min, avg, max) = (4.552, 4.638, 4.745), stdev = 0.098
  CI (99.9%): [2.845, 6.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.379 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.875 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.365 ±(99.9%) 0.021 ms/op
Iteration   1: 3.982 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.892 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.567 ms/op
                 createUser·p0.999:  24.740 ms/op
                 createUser·p0.9999: 27.452 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   2: 3.848 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.475 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   7.668 ms/op
                 createUser·p0.999:  13.369 ms/op
                 createUser·p0.9999: 28.662 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 3.944 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.997 ms/op
                 createUser·p0.999:  27.129 ms/op
                 createUser·p0.9999: 33.027 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244513
  mean =      3.924 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 499 
    [ 2.500,  5.000) = 233518 
    [ 5.000,  7.500) = 8125 
    [ 7.500, 10.000) = 1717 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     32.050 ms/op
     p(99.9990) =     34.028 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.625 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.014 ms/op
Iteration   1: 3.930 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.817 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  23.921 ms/op
                 existUser·p0.9999: 26.079 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   2: 3.780 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.866 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  16.712 ms/op
                 existUser·p0.9999: 27.215 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   3: 3.977 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.927 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   7.291 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 31.947 ms/op
                 existUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246574
  mean =      3.894 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 234171 
    [ 5.000,  7.500) = 10411 
    [ 7.500, 10.000) = 1325 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.817 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     16.702 ms/op
     p(99.9900) =     31.152 ms/op
     p(99.9990) =     32.233 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.038 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.016 ms/op
Iteration   1: 4.094 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.071 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.719 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  14.385 ms/op
                 getUser·p0.9999: 26.718 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   2: 4.110 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.679 ms/op
                 getUser·p0.999:  26.247 ms/op
                 getUser·p0.9999: 29.590 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 3.919 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  13.861 ms/op
                 getUser·p0.9999: 29.977 ms/op
                 getUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237720
  mean =      4.039 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 223246 
    [ 5.000,  7.500) = 11509 
    [ 7.500, 10.000) = 1986 
    [10.000, 12.500) = 481 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     23.063 ms/op
     p(99.9900) =     29.269 ms/op
     p(99.9990) =     30.273 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_345, OpenJDK 64-Bit Server VM, 25.345-b01
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.345-1/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.756 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 5.639 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.268 ±(99.9%) 0.024 ms/op
Iteration   1: 4.643 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  22.582 ms/op
                 listUser·p0.9999: 26.335 ms/op
                 listUser·p1.00:   27.754 ms/op

Iteration   2: 4.739 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.610 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  23.443 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   3: 4.610 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  17.713 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205849
  mean =      4.663 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 178615 
    [ 5.000,  7.500) = 22491 
    [ 7.500, 10.000) = 3604 
    [10.000, 12.500) = 464 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     21.796 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.804 ± 6.050  ops/ms
ClientPb.existUser                       thrpt       3   8.120 ± 1.421  ops/ms
ClientPb.getUser                         thrpt       3   7.967 ± 9.761  ops/ms
ClientPb.listUser                        thrpt       3   6.853 ± 1.793  ops/ms
ClientPb.createUser                       avgt       3   3.990 ± 0.799   ms/op
ClientPb.existUser                        avgt       3   3.745 ± 1.047   ms/op
ClientPb.getUser                          avgt       3   4.023 ± 1.749   ms/op
ClientPb.listUser                         avgt       3   4.638 ± 1.793   ms/op
ClientPb.createUser                     sample  244513   3.924 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.475           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.414           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.576           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.050           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.210           ms/op
ClientPb.existUser                      sample  246574   3.894 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.817           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.078           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.702           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.152           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.834           ms/op
ClientPb.getUser                        sample  237720   4.039 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.575           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.063           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.269           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.507           ms/op
ClientPb.listUser                       sample  205849   4.663 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.610           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.796           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.952           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.754           ms/op
