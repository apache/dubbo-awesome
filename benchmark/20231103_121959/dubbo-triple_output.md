# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.615 ops/ms
# Warmup Iteration   2: 3.539 ops/ms
# Warmup Iteration   3: 6.661 ops/ms
Iteration   1: 7.002 ops/ms
Iteration   2: 7.737 ops/ms
Iteration   3: 7.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.454 ±(99.9%) 7.218 ops/ms [Average]
  (min, avg, max) = (7.002, 7.454, 7.737), stdev = 0.396
  CI (99.9%): [0.237, 14.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.095 ops/ms
# Warmup Iteration   2: 6.474 ops/ms
# Warmup Iteration   3: 8.029 ops/ms
Iteration   1: 8.126 ops/ms
Iteration   2: 8.441 ops/ms
Iteration   3: 8.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.254 ±(99.9%) 3.020 ops/ms [Average]
  (min, avg, max) = (8.126, 8.254, 8.441), stdev = 0.166
  CI (99.9%): [5.233, 11.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.347 ops/ms
# Warmup Iteration   2: 6.677 ops/ms
# Warmup Iteration   3: 7.432 ops/ms
Iteration   1: 7.660 ops/ms
Iteration   2: 7.906 ops/ms
Iteration   3: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.867 ±(99.9%) 3.481 ops/ms [Average]
  (min, avg, max) = (7.660, 7.867, 8.036), stdev = 0.191
  CI (99.9%): [4.386, 11.349] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.189 ops/ms
# Warmup Iteration   2: 5.262 ops/ms
# Warmup Iteration   3: 6.451 ops/ms
Iteration   1: 6.310 ops/ms
Iteration   2: 6.635 ops/ms
Iteration   3: 6.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.564 ±(99.9%) 4.135 ops/ms [Average]
  (min, avg, max) = (6.310, 6.564, 6.746), stdev = 0.227
  CI (99.9%): [2.429, 10.698] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.736 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.371 ±(99.9%) 0.004 ms/op
Iteration   1: 3.935 ±(99.9%) 0.010 ms/op
Iteration   2: 3.992 ±(99.9%) 0.005 ms/op
Iteration   3: 4.011 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.979 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (3.935, 3.979, 4.011), stdev = 0.040
  CI (99.9%): [3.255, 4.704] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.229 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.004 ms/op
Iteration   1: 3.849 ±(99.9%) 0.007 ms/op
Iteration   2: 3.902 ±(99.9%) 0.007 ms/op
Iteration   3: 4.094 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.948 ±(99.9%) 2.356 ms/op [Average]
  (min, avg, max) = (3.849, 3.948, 4.094), stdev = 0.129
  CI (99.9%): [1.592, 6.305] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.038 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.145 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.344 ±(99.9%) 0.006 ms/op
Iteration   1: 4.207 ±(99.9%) 0.006 ms/op
Iteration   2: 4.117 ±(99.9%) 0.008 ms/op
Iteration   3: 4.110 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.145 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (4.110, 4.145, 4.207), stdev = 0.054
  CI (99.9%): [3.154, 5.135] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.159 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.063 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.758 ±(99.9%) 0.008 ms/op
Iteration   1: 4.805 ±(99.9%) 0.012 ms/op
Iteration   2: 4.730 ±(99.9%) 0.007 ms/op
Iteration   3: 4.876 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.804 ±(99.9%) 1.339 ms/op [Average]
  (min, avg, max) = (4.730, 4.804, 4.876), stdev = 0.073
  CI (99.9%): [3.465, 6.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.835 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.509 ±(99.9%) 0.018 ms/op
Iteration   1: 4.144 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  13.766 ms/op
                 createUser·p0.9999: 25.539 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   2: 4.132 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.381 ms/op
                 createUser·p0.99:   7.840 ms/op
                 createUser·p0.999:  27.476 ms/op
                 createUser·p0.9999: 32.795 ms/op
                 createUser·p1.00:   34.341 ms/op

Iteration   3: 4.238 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.817 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.889 ms/op
                 createUser·p0.999:  23.348 ms/op
                 createUser·p0.9999: 30.602 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229955
  mean =      4.171 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 399 
    [ 2.500,  5.000) = 210084 
    [ 5.000,  7.500) = 16567 
    [ 7.500, 10.000) = 2137 
    [10.000, 12.500) = 438 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      7.860 ms/op
     p(99.9000) =     22.157 ms/op
     p(99.9900) =     31.785 ms/op
     p(99.9990) =     33.433 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.777 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.012 ms/op
Iteration   1: 3.867 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  10.360 ms/op
                 existUser·p0.9999: 25.911 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   2: 3.908 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  25.821 ms/op
                 existUser·p0.9999: 28.502 ms/op
                 existUser·p1.00:   29.196 ms/op

Iteration   3: 4.027 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.381 ms/op
                 existUser·p0.999:  13.871 ms/op
                 existUser·p0.9999: 30.208 ms/op
                 existUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243930
  mean =      3.933 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 347 
    [ 2.500,  5.000) = 232746 
    [ 5.000,  7.500) = 8879 
    [ 7.500, 10.000) = 1226 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     29.183 ms/op
     p(99.9990) =     32.122 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.669 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.892 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.013 ms/op
Iteration   1: 4.352 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.038 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   6.701 ms/op
                 getUser·p0.99:   9.800 ms/op
                 getUser·p0.999:  17.670 ms/op
                 getUser·p0.9999: 26.924 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   2: 4.124 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   4.002 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  25.373 ms/op
                 getUser·p0.9999: 27.876 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 4.123 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   8.143 ms/op
                 getUser·p0.999:  13.271 ms/op
                 getUser·p0.9999: 32.940 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 228700
  mean =      4.197 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 211592 
    [ 5.000,  7.500) = 13079 
    [ 7.500, 10.000) = 2870 
    [10.000, 12.500) = 682 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     18.982 ms/op
     p(99.9900) =     31.511 ms/op
     p(99.9990) =     33.610 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.289 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.416 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 4.841 ±(99.9%) 0.015 ms/op
Iteration   1: 4.893 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.308 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  23.484 ms/op
                 listUser·p0.9999: 25.507 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 5.039 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  20.792 ms/op
                 listUser·p0.9999: 25.766 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   3: 4.930 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  16.718 ms/op
                 listUser·p0.9999: 21.694 ms/op
                 listUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193699
  mean =      4.953 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 135465 
    [ 5.000,  7.500) = 53108 
    [ 7.500, 10.000) = 3757 
    [10.000, 12.500) = 685 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     26.610 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.454 ± 7.218  ops/ms
ClientPb.existUser                       thrpt       3   8.254 ± 3.020  ops/ms
ClientPb.getUser                         thrpt       3   7.867 ± 3.481  ops/ms
ClientPb.listUser                        thrpt       3   6.564 ± 4.135  ops/ms
ClientPb.createUser                       avgt       3   3.979 ± 0.725   ms/op
ClientPb.existUser                        avgt       3   3.948 ± 2.356   ms/op
ClientPb.getUser                          avgt       3   4.145 ± 0.990   ms/op
ClientPb.listUser                         avgt       3   4.804 ± 1.339   ms/op
ClientPb.createUser                     sample  229955   4.171 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.561           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.907           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.860           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.157           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.785           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.341           ms/op
ClientPb.existUser                      sample  243930   3.933 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.045           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.183           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.932           ms/op
ClientPb.getUser                        sample  228700   4.197 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.430           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.743           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.331           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.982           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.511           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.948           ms/op
ClientPb.listUser                       sample  193699   4.953 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.126           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.266           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.330           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
