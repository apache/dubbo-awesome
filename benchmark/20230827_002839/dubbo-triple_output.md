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
# Warmup Iteration   1: 1.685 ops/ms
# Warmup Iteration   2: 3.490 ops/ms
# Warmup Iteration   3: 7.254 ops/ms
Iteration   1: 7.335 ops/ms
Iteration   2: 7.900 ops/ms
Iteration   3: 7.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.686 ±(99.9%) 5.594 ops/ms [Average]
  (min, avg, max) = (7.335, 7.686, 7.900), stdev = 0.307
  CI (99.9%): [2.092, 13.280] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.232 ops/ms
# Warmup Iteration   2: 5.496 ops/ms
# Warmup Iteration   3: 7.850 ops/ms
Iteration   1: 8.088 ops/ms
Iteration   2: 8.345 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.158 ±(99.9%) 2.976 ops/ms [Average]
  (min, avg, max) = (8.042, 8.158, 8.345), stdev = 0.163
  CI (99.9%): [5.182, 11.135] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.013 ops/ms
# Warmup Iteration   2: 5.990 ops/ms
# Warmup Iteration   3: 7.419 ops/ms
Iteration   1: 7.383 ops/ms
Iteration   2: 7.692 ops/ms
Iteration   3: 7.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.620 ±(99.9%) 3.848 ops/ms [Average]
  (min, avg, max) = (7.383, 7.620, 7.786), stdev = 0.211
  CI (99.9%): [3.772, 11.468] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.057 ops/ms
# Warmup Iteration   2: 5.452 ops/ms
# Warmup Iteration   3: 6.360 ops/ms
Iteration   1: 6.365 ops/ms
Iteration   2: 6.704 ops/ms
Iteration   3: 6.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.612 ±(99.9%) 3.942 ops/ms [Average]
  (min, avg, max) = (6.365, 6.612, 6.766), stdev = 0.216
  CI (99.9%): [2.670, 10.554] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.003 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.326 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.585 ±(99.9%) 0.006 ms/op
Iteration   1: 4.323 ±(99.9%) 0.006 ms/op
Iteration   2: 4.016 ±(99.9%) 0.009 ms/op
Iteration   3: 4.031 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.123 ±(99.9%) 3.153 ms/op [Average]
  (min, avg, max) = (4.016, 4.123, 4.323), stdev = 0.173
  CI (99.9%): [0.970, 7.276] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.037 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.682 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.009 ms/op
Iteration   1: 3.938 ±(99.9%) 0.005 ms/op
Iteration   2: 4.206 ±(99.9%) 0.009 ms/op
Iteration   3: 4.213 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.119 ±(99.9%) 2.853 ms/op [Average]
  (min, avg, max) = (3.938, 4.119, 4.213), stdev = 0.156
  CI (99.9%): [1.266, 6.972] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.734 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.655 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.007 ms/op
Iteration   1: 4.055 ±(99.9%) 0.005 ms/op
Iteration   2: 4.179 ±(99.9%) 0.006 ms/op
Iteration   3: 4.037 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.090 ±(99.9%) 1.406 ms/op [Average]
  (min, avg, max) = (4.037, 4.090, 4.179), stdev = 0.077
  CI (99.9%): [2.684, 5.497] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.741 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.448 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.074 ±(99.9%) 0.006 ms/op
Iteration   1: 5.071 ±(99.9%) 0.006 ms/op
Iteration   2: 4.968 ±(99.9%) 0.010 ms/op
Iteration   3: 4.922 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.987 ±(99.9%) 1.398 ms/op [Average]
  (min, avg, max) = (4.922, 4.987, 5.071), stdev = 0.077
  CI (99.9%): [3.589, 6.385] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.021 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.206 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.652 ±(99.9%) 0.022 ms/op
Iteration   1: 4.290 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.855 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  14.316 ms/op
                 createUser·p0.9999: 27.019 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   2: 4.079 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.747 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   8.159 ms/op
                 createUser·p0.999:  25.788 ms/op
                 createUser·p0.9999: 28.743 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   3: 4.151 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   7.889 ms/op
                 createUser·p0.999:  29.065 ms/op
                 createUser·p0.9999: 36.504 ms/op
                 createUser·p1.00:   38.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229966
  mean =      4.172 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 422 
    [ 2.500,  5.000) = 211512 
    [ 5.000,  7.500) = 14094 
    [ 7.500, 10.000) = 2618 
    [10.000, 12.500) = 751 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     25.593 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     38.287 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.378 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.012 ms/op
Iteration   1: 4.010 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.800 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   7.635 ms/op
                 existUser·p0.999:  12.436 ms/op
                 existUser·p0.9999: 26.119 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 3.959 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  24.779 ms/op
                 existUser·p0.9999: 26.996 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 4.136 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.958 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   8.290 ms/op
                 existUser·p0.999:  20.251 ms/op
                 existUser·p0.9999: 31.392 ms/op
                 existUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 237829
  mean =      4.034 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 285 
    [ 2.500,  5.000) = 220205 
    [ 5.000,  7.500) = 14541 
    [ 7.500, 10.000) = 1825 
    [10.000, 12.500) = 573 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     30.426 ms/op
     p(99.9990) =     32.272 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.647 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.051 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.014 ms/op
Iteration   1: 4.271 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   6.734 ms/op
                 getUser·p0.99:   9.339 ms/op
                 getUser·p0.999:  19.030 ms/op
                 getUser·p0.9999: 26.214 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   2: 4.221 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  25.494 ms/op
                 getUser·p0.9999: 38.383 ms/op
                 getUser·p1.00:   41.419 ms/op

Iteration   3: 3.953 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  11.387 ms/op
                 getUser·p0.9999: 30.626 ms/op
                 getUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231613
  mean =      4.144 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 213862 
    [ 5.000, 10.000) = 16563 
    [10.000, 15.000) = 919 
    [15.000, 20.000) = 39 
    [20.000, 25.000) = 62 
    [25.000, 30.000) = 115 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     32.705 ms/op
     p(99.9990) =     40.860 ms/op
     p(99.9999) =     41.419 ms/op
    p(100.0000) =     41.419 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.189 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.525 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.004 ±(99.9%) 0.019 ms/op
Iteration   1: 4.817 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  27.117 ms/op
                 listUser·p0.9999: 29.521 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   2: 4.710 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 18.757 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 4.576 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  18.720 ms/op
                 listUser·p0.9999: 21.365 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204252
  mean =      4.699 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 174877 
    [ 5.000,  7.500) = 23519 
    [ 7.500, 10.000) = 4194 
    [10.000, 12.500) = 963 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.657 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     28.611 ms/op
     p(99.9990) =     30.145 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.686 ± 5.594  ops/ms
ClientPb.existUser                       thrpt       3   8.158 ± 2.976  ops/ms
ClientPb.getUser                         thrpt       3   7.620 ± 3.848  ops/ms
ClientPb.listUser                        thrpt       3   6.612 ± 3.942  ops/ms
ClientPb.createUser                       avgt       3   4.123 ± 3.153   ms/op
ClientPb.existUser                        avgt       3   4.119 ± 2.853   ms/op
ClientPb.getUser                          avgt       3   4.090 ± 1.406   ms/op
ClientPb.listUser                         avgt       3   4.987 ± 1.398   ms/op
ClientPb.createUser                     sample  229966   4.172 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.745           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.841           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.438           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.593           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.455           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.994           ms/op
ClientPb.existUser                      sample  237829   4.034 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.438           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.710           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.782           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.251           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.426           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.096           ms/op
ClientPb.getUser                        sample  231613   4.144 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.094           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.956           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.705           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.419           ms/op
ClientPb.listUser                       sample  204252   4.699 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.657           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.404           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.694           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.611           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.310           ms/op
