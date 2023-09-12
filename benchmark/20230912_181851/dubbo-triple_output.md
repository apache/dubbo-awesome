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
# Warmup Iteration   1: 1.147 ops/ms
# Warmup Iteration   2: 2.806 ops/ms
# Warmup Iteration   3: 5.146 ops/ms
Iteration   1: 5.498 ops/ms
Iteration   2: 5.723 ops/ms
Iteration   3: 5.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.706 ±(99.9%) 3.648 ops/ms [Average]
  (min, avg, max) = (5.498, 5.706, 5.897), stdev = 0.200
  CI (99.9%): [2.058, 9.354] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.745 ops/ms
# Warmup Iteration   2: 5.091 ops/ms
# Warmup Iteration   3: 6.080 ops/ms
Iteration   1: 6.182 ops/ms
Iteration   2: 6.171 ops/ms
Iteration   3: 5.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.110 ±(99.9%) 2.120 ops/ms [Average]
  (min, avg, max) = (5.976, 6.110, 6.182), stdev = 0.116
  CI (99.9%): [3.990, 8.230] (assumes normal distribution)


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
# Warmup Iteration   1: 1.482 ops/ms
# Warmup Iteration   2: 4.262 ops/ms
# Warmup Iteration   3: 5.820 ops/ms
Iteration   1: 5.757 ops/ms
Iteration   2: 5.887 ops/ms
Iteration   3: 5.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.814 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (5.757, 5.814, 5.887), stdev = 0.066
  CI (99.9%): [4.601, 7.026] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.619 ops/ms
# Warmup Iteration   2: 4.102 ops/ms
# Warmup Iteration   3: 4.912 ops/ms
Iteration   1: 5.070 ops/ms
Iteration   2: 4.789 ops/ms
Iteration   3: 5.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.985 ±(99.9%) 3.108 ops/ms [Average]
  (min, avg, max) = (4.789, 4.985, 5.097), stdev = 0.170
  CI (99.9%): [1.878, 8.093] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 19.680 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.690 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.893 ±(99.9%) 0.010 ms/op
Iteration   1: 5.795 ±(99.9%) 0.013 ms/op
Iteration   2: 5.628 ±(99.9%) 0.013 ms/op
Iteration   3: 5.538 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.654 ±(99.9%) 2.381 ms/op [Average]
  (min, avg, max) = (5.538, 5.654, 5.795), stdev = 0.130
  CI (99.9%): [3.273, 8.034] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.317 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.977 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.319 ±(99.9%) 0.010 ms/op
Iteration   1: 5.268 ±(99.9%) 0.010 ms/op
Iteration   2: 5.501 ±(99.9%) 0.006 ms/op
Iteration   3: 5.325 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.365 ±(99.9%) 2.222 ms/op [Average]
  (min, avg, max) = (5.268, 5.365, 5.501), stdev = 0.122
  CI (99.9%): [3.143, 7.587] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.455 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.956 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.641 ±(99.9%) 0.011 ms/op
Iteration   1: 5.485 ±(99.9%) 0.009 ms/op
Iteration   2: 5.560 ±(99.9%) 0.014 ms/op
Iteration   3: 5.419 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.488 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (5.419, 5.488, 5.560), stdev = 0.071
  CI (99.9%): [4.201, 6.775] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.220 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 7.436 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.373 ±(99.9%) 0.017 ms/op
Iteration   1: 6.517 ±(99.9%) 0.015 ms/op
Iteration   2: 6.648 ±(99.9%) 0.012 ms/op
Iteration   3: 6.143 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.436 ±(99.9%) 4.776 ms/op [Average]
  (min, avg, max) = (6.143, 6.436, 6.648), stdev = 0.262
  CI (99.9%): [1.660, 11.213] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.598 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.835 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.766 ±(99.9%) 0.023 ms/op
Iteration   1: 5.587 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   7.094 ms/op
                 createUser·p0.95:   7.987 ms/op
                 createUser·p0.99:   10.797 ms/op
                 createUser·p0.999:  25.642 ms/op
                 createUser·p0.9999: 28.657 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   2: 5.503 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.520 ms/op
                 createUser·p0.99:   10.486 ms/op
                 createUser·p0.999:  28.453 ms/op
                 createUser·p0.9999: 35.861 ms/op
                 createUser·p1.00:   36.897 ms/op

Iteration   3: 5.683 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   10.617 ms/op
                 createUser·p0.999:  27.558 ms/op
                 createUser·p0.9999: 34.587 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171519
  mean =      5.590 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 61406 
    [ 5.000,  7.500) = 98260 
    [ 7.500, 10.000) = 9553 
    [10.000, 12.500) = 1366 
    [12.500, 15.000) = 464 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     26.263 ms/op
     p(99.9900) =     34.986 ms/op
     p(99.9990) =     36.662 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.920 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 6.604 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 5.438 ±(99.9%) 0.021 ms/op
Iteration   1: 5.314 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.930 ms/op
                 existUser·p0.99:   10.584 ms/op
                 existUser·p0.999:  24.864 ms/op
                 existUser·p0.9999: 30.768 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   2: 5.374 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.668 ms/op
                 existUser·p0.95:   8.217 ms/op
                 existUser·p0.99:   10.879 ms/op
                 existUser·p0.999:  16.828 ms/op
                 existUser·p0.9999: 30.674 ms/op
                 existUser·p1.00:   31.850 ms/op

Iteration   3: 5.262 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.388 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.274 ms/op
                 existUser·p0.99:   11.256 ms/op
                 existUser·p0.999:  27.650 ms/op
                 existUser·p0.9999: 30.081 ms/op
                 existUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180508
  mean =      5.316 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 89257 
    [ 5.000,  7.500) = 80432 
    [ 7.500, 10.000) = 8127 
    [10.000, 12.500) = 1722 
    [12.500, 15.000) = 481 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     24.314 ms/op
     p(99.9900) =     30.604 ms/op
     p(99.9990) =     31.824 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.797 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.900 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.811 ±(99.9%) 0.025 ms/op
Iteration   1: 5.430 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.482 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.905 ms/op
                 getUser·p0.99:   11.223 ms/op
                 getUser·p0.999:  21.237 ms/op
                 getUser·p0.9999: 24.186 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 5.796 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   7.299 ms/op
                 getUser·p0.95:   8.913 ms/op
                 getUser·p0.99:   12.829 ms/op
                 getUser·p0.999:  24.471 ms/op
                 getUser·p0.9999: 41.581 ms/op
                 getUser·p1.00:   42.271 ms/op

Iteration   3: 5.583 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.449 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   8.092 ms/op
                 getUser·p0.99:   10.842 ms/op
                 getUser·p0.999:  24.631 ms/op
                 getUser·p0.9999: 28.222 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171430
  mean =      5.599 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 63600 
    [ 5.000, 10.000) = 104248 
    [10.000, 15.000) = 3073 
    [15.000, 20.000) = 288 
    [20.000, 25.000) = 119 
    [25.000, 30.000) = 71 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.359 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      8.266 ms/op
     p(99.0000) =     11.813 ms/op
     p(99.9000) =     22.156 ms/op
     p(99.9900) =     40.623 ms/op
     p(99.9990) =     42.177 ms/op
     p(99.9999) =     42.271 ms/op
    p(100.0000) =     42.271 ms/op


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
# Warmup Iteration   1: 19.987 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 7.929 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.705 ±(99.9%) 0.030 ms/op
Iteration   1: 6.421 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.517 ms/op
                 listUser·p0.999:  27.596 ms/op
                 listUser·p0.9999: 31.393 ms/op
                 listUser·p1.00:   31.654 ms/op

Iteration   2: 6.403 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.080 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.435 ms/op
                 listUser·p0.999:  28.937 ms/op
                 listUser·p0.9999: 36.571 ms/op
                 listUser·p1.00:   37.159 ms/op

Iteration   3: 6.540 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.015 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  23.996 ms/op
                 listUser·p0.9999: 30.439 ms/op
                 listUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148712
  mean =      6.454 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 5402 
    [ 5.000,  7.500) = 124659 
    [ 7.500, 10.000) = 13745 
    [10.000, 12.500) = 3465 
    [12.500, 15.000) = 846 
    [15.000, 17.500) = 255 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      6.078 ms/op
     p(90.0000) =      7.799 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     12.401 ms/op
     p(99.9000) =     27.216 ms/op
     p(99.9900) =     35.005 ms/op
     p(99.9990) =     37.031 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.706 ± 3.648  ops/ms
ClientPb.existUser                       thrpt       3   6.110 ± 2.120  ops/ms
ClientPb.getUser                         thrpt       3   5.814 ± 1.212  ops/ms
ClientPb.listUser                        thrpt       3   4.985 ± 3.108  ops/ms
ClientPb.createUser                       avgt       3   5.654 ± 2.381   ms/op
ClientPb.existUser                        avgt       3   5.365 ± 2.222   ms/op
ClientPb.getUser                          avgt       3   5.488 ± 1.287   ms/op
ClientPb.listUser                         avgt       3   6.436 ± 4.776   ms/op
ClientPb.createUser                     sample  171519   5.590 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.399           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.963           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.913           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.263           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.986           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.897           ms/op
ClientPb.existUser                      sample  180508   5.316 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.864           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.863           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.314           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.604           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  171430   5.599 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.359           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.235           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.963           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.266           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.813           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.156           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.623           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.271           ms/op
ClientPb.listUser                       sample  148712   6.454 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.966           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.078           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.799           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.401           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.216           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.005           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.159           ms/op
