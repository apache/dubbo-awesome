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
# Warmup Iteration   1: 0.887 ops/ms
# Warmup Iteration   2: 1.999 ops/ms
# Warmup Iteration   3: 4.256 ops/ms
Iteration   1: 4.985 ops/ms
Iteration   2: 5.295 ops/ms
Iteration   3: 5.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.196 ±(99.9%) 3.349 ops/ms [Average]
  (min, avg, max) = (4.985, 5.196, 5.310), stdev = 0.184
  CI (99.9%): [1.848, 8.545] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.330 ops/ms
# Warmup Iteration   2: 3.945 ops/ms
# Warmup Iteration   3: 5.255 ops/ms
Iteration   1: 5.404 ops/ms
Iteration   2: 5.630 ops/ms
Iteration   3: 5.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.534 ±(99.9%) 2.131 ops/ms [Average]
  (min, avg, max) = (5.404, 5.534, 5.630), stdev = 0.117
  CI (99.9%): [3.402, 7.665] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.333 ops/ms
# Warmup Iteration   2: 3.840 ops/ms
# Warmup Iteration   3: 5.351 ops/ms
Iteration   1: 5.387 ops/ms
Iteration   2: 5.269 ops/ms
Iteration   3: 5.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.318 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (5.269, 5.318, 5.387), stdev = 0.062
  CI (99.9%): [4.186, 6.450] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.221 ops/ms
# Warmup Iteration   2: 3.266 ops/ms
# Warmup Iteration   3: 4.370 ops/ms
Iteration   1: 4.447 ops/ms
Iteration   2: 4.651 ops/ms
Iteration   3: 4.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.553 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (4.447, 4.553, 4.651), stdev = 0.102
  CI (99.9%): [2.687, 6.418] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.661 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 7.630 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.160 ±(99.9%) 0.028 ms/op
Iteration   1: 6.299 ±(99.9%) 0.017 ms/op
Iteration   2: 6.091 ±(99.9%) 0.016 ms/op
Iteration   3: 5.979 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.123 ±(99.9%) 2.959 ms/op [Average]
  (min, avg, max) = (5.979, 6.123, 6.299), stdev = 0.162
  CI (99.9%): [3.164, 9.082] (assumes normal distribution)


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
# Warmup Iteration   1: 20.851 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 7.298 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.025 ±(99.9%) 0.015 ms/op
Iteration   1: 5.714 ±(99.9%) 0.013 ms/op
Iteration   2: 5.783 ±(99.9%) 0.011 ms/op
Iteration   3: 5.645 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.714 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (5.645, 5.714, 5.783), stdev = 0.069
  CI (99.9%): [4.453, 6.975] (assumes normal distribution)


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
# Warmup Iteration   1: 20.453 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 7.242 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.168 ±(99.9%) 0.008 ms/op
Iteration   1: 5.954 ±(99.9%) 0.012 ms/op
Iteration   2: 5.986 ±(99.9%) 0.013 ms/op
Iteration   3: 5.970 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.970 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (5.954, 5.970, 5.986), stdev = 0.016
  CI (99.9%): [5.684, 6.256] (assumes normal distribution)


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
# Warmup Iteration   1: 21.566 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 8.963 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 7.338 ±(99.9%) 0.011 ms/op
Iteration   1: 7.015 ±(99.9%) 0.013 ms/op
Iteration   2: 7.057 ±(99.9%) 0.015 ms/op
Iteration   3: 7.054 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.042 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (7.015, 7.042, 7.057), stdev = 0.024
  CI (99.9%): [6.610, 7.474] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.450 ±(99.9%) 0.399 ms/op
# Warmup Iteration   2: 7.736 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.579 ±(99.9%) 0.032 ms/op
Iteration   1: 6.011 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.654 ms/op
                 createUser·p0.50:   5.644 ms/op
                 createUser·p0.90:   7.537 ms/op
                 createUser·p0.95:   8.634 ms/op
                 createUser·p0.99:   11.321 ms/op
                 createUser·p0.999:  30.474 ms/op
                 createUser·p0.9999: 39.258 ms/op
                 createUser·p1.00:   39.453 ms/op

Iteration   2: 6.240 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   5.751 ms/op
                 createUser·p0.90:   8.217 ms/op
                 createUser·p0.95:   9.388 ms/op
                 createUser·p0.99:   12.763 ms/op
                 createUser·p0.999:  29.219 ms/op
                 createUser·p0.9999: 37.133 ms/op
                 createUser·p1.00:   38.207 ms/op

Iteration   3: 6.119 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   5.718 ms/op
                 createUser·p0.90:   7.799 ms/op
                 createUser·p0.95:   9.044 ms/op
                 createUser·p0.99:   12.468 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 34.129 ms/op
                 createUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 156797
  mean =      6.122 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 26000 
    [ 5.000,  7.500) = 111631 
    [ 7.500, 10.000) = 14625 
    [10.000, 12.500) = 3104 
    [12.500, 15.000) = 785 
    [15.000, 17.500) = 324 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 52 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      5.702 ms/op
     p(90.0000) =      7.807 ms/op
     p(95.0000) =      9.044 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     27.820 ms/op
     p(99.9900) =     37.114 ms/op
     p(99.9990) =     39.453 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.021 ±(99.9%) 0.358 ms/op
# Warmup Iteration   2: 6.970 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.795 ±(99.9%) 0.024 ms/op
Iteration   1: 6.009 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.650 ms/op
                 existUser·p0.50:   5.546 ms/op
                 existUser·p0.90:   8.077 ms/op
                 existUser·p0.95:   9.486 ms/op
                 existUser·p0.99:   12.883 ms/op
                 existUser·p0.999:  16.511 ms/op
                 existUser·p0.9999: 29.984 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   2: 6.011 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   2.527 ms/op
                 existUser·p0.50:   5.480 ms/op
                 existUser·p0.90:   8.053 ms/op
                 existUser·p0.95:   9.486 ms/op
                 existUser·p0.99:   13.500 ms/op
                 existUser·p0.999:  28.967 ms/op
                 existUser·p0.9999: 37.445 ms/op
                 existUser·p1.00:   37.880 ms/op

Iteration   3: 5.844 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.507 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.692 ms/op
                 existUser·p0.95:   9.142 ms/op
                 existUser·p0.99:   12.239 ms/op
                 existUser·p0.999:  17.433 ms/op
                 existUser·p0.9999: 36.407 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 161138
  mean =      5.954 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 38103 
    [ 5.000,  7.500) = 102578 
    [ 7.500, 10.000) = 14569 
    [10.000, 12.500) = 4035 
    [12.500, 15.000) = 1253 
    [15.000, 17.500) = 406 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.507 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      7.971 ms/op
     p(95.0000) =      9.355 ms/op
     p(99.0000) =     12.894 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     36.431 ms/op
     p(99.9990) =     37.880 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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
# Warmup Iteration   1: 21.871 ±(99.9%) 0.381 ms/op
# Warmup Iteration   2: 9.225 ±(99.9%) 0.084 ms/op
# Warmup Iteration   3: 6.323 ±(99.9%) 0.026 ms/op
Iteration   1: 6.241 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.810 ms/op
                 getUser·p0.50:   5.784 ms/op
                 getUser·p0.90:   7.782 ms/op
                 getUser·p0.95:   9.486 ms/op
                 getUser·p0.99:   13.495 ms/op
                 getUser·p0.999:  27.263 ms/op
                 getUser·p0.9999: 35.169 ms/op
                 getUser·p1.00:   44.696 ms/op

Iteration   2: 6.128 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   5.784 ms/op
                 getUser·p0.90:   7.627 ms/op
                 getUser·p0.95:   8.946 ms/op
                 getUser·p0.99:   11.977 ms/op
                 getUser·p0.999:  19.868 ms/op
                 getUser·p0.9999: 31.912 ms/op
                 getUser·p1.00:   32.932 ms/op

Iteration   3: 6.223 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.785 ms/op
                 getUser·p0.50:   5.792 ms/op
                 getUser·p0.90:   7.758 ms/op
                 getUser·p0.95:   9.208 ms/op
                 getUser·p0.99:   13.599 ms/op
                 getUser·p0.999:  31.949 ms/op
                 getUser·p0.9999: 36.691 ms/op
                 getUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 154850
  mean =      6.197 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16786 
    [ 5.000, 10.000) = 132731 
    [10.000, 15.000) = 4646 
    [15.000, 20.000) = 431 
    [20.000, 25.000) = 64 
    [25.000, 30.000) = 91 
    [30.000, 35.000) = 83 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      5.784 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     13.091 ms/op
     p(99.9000) =     26.917 ms/op
     p(99.9900) =     35.624 ms/op
     p(99.9990) =     40.741 ms/op
     p(99.9999) =     44.696 ms/op
    p(100.0000) =     44.696 ms/op


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
# Warmup Iteration   1: 21.933 ±(99.9%) 0.370 ms/op
# Warmup Iteration   2: 8.846 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 7.203 ±(99.9%) 0.034 ms/op
Iteration   1: 7.143 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   6.668 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   10.453 ms/op
                 listUser·p0.99:   13.908 ms/op
                 listUser·p0.999:  32.590 ms/op
                 listUser·p0.9999: 35.783 ms/op
                 listUser·p1.00:   36.045 ms/op

Iteration   2: 7.064 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   6.619 ms/op
                 listUser·p0.90:   8.733 ms/op
                 listUser·p0.95:   10.011 ms/op
                 listUser·p0.99:   13.849 ms/op
                 listUser·p0.999:  30.269 ms/op
                 listUser·p0.9999: 34.010 ms/op
                 listUser·p1.00:   37.487 ms/op

Iteration   3: 7.154 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   3.121 ms/op
                 listUser·p0.50:   6.701 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.355 ms/op
                 listUser·p0.99:   14.189 ms/op
                 listUser·p0.999:  31.031 ms/op
                 listUser·p0.9999: 34.537 ms/op
                 listUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 134741
  mean =      7.120 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 1498 
    [ 5.000,  7.500) = 100566 
    [ 7.500, 10.000) = 25041 
    [10.000, 12.500) = 5251 
    [12.500, 15.000) = 1377 
    [15.000, 17.500) = 406 
    [17.500, 20.000) = 200 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 105 
    [32.500, 35.000) = 80 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      6.660 ms/op
     p(90.0000) =      8.847 ms/op
     p(95.0000) =     10.256 ms/op
     p(99.0000) =     13.976 ms/op
     p(99.9000) =     31.081 ms/op
     p(99.9900) =     35.100 ms/op
     p(99.9990) =     37.122 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# Run complete. Total time: 00:13:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.196 ± 3.349  ops/ms
ClientPb.existUser                       thrpt       3   5.534 ± 2.131  ops/ms
ClientPb.getUser                         thrpt       3   5.318 ± 1.132  ops/ms
ClientPb.listUser                        thrpt       3   4.553 ± 1.865  ops/ms
ClientPb.createUser                       avgt       3   6.123 ± 2.959   ms/op
ClientPb.existUser                        avgt       3   5.714 ± 1.261   ms/op
ClientPb.getUser                          avgt       3   5.970 ± 0.286   ms/op
ClientPb.listUser                         avgt       3   7.042 ± 0.432   ms/op
ClientPb.createUser                     sample  156797   6.122 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.077           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.807           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.044           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.288           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.820           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.114           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.453           ms/op
ClientPb.existUser                      sample  161138   5.954 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.971           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.355           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.894           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.579           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.431           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.880           ms/op
ClientPb.getUser                        sample  154850   6.197 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.126           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.717           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.224           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.091           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.917           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.624           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.696           ms/op
ClientPb.listUser                       sample  134741   7.120 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.649           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.660           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.256           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.976           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.081           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.100           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.487           ms/op
