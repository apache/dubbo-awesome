# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.590 ops/ms
# Warmup Iteration   2: 3.411 ops/ms
# Warmup Iteration   3: 6.465 ops/ms
Iteration   1: 7.385 ops/ms
Iteration   2: 8.185 ops/ms
Iteration   3: 8.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.976 ±(99.9%) 9.482 ops/ms [Average]
  (min, avg, max) = (7.385, 7.976, 8.360), stdev = 0.520
  CI (99.9%): [≈ 0, 17.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.232 ops/ms
# Warmup Iteration   2: 6.503 ops/ms
# Warmup Iteration   3: 7.923 ops/ms
Iteration   1: 8.353 ops/ms
Iteration   2: 8.689 ops/ms
Iteration   3: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.434 ±(99.9%) 4.115 ops/ms [Average]
  (min, avg, max) = (8.259, 8.434, 8.689), stdev = 0.226
  CI (99.9%): [4.319, 12.548] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.176 ops/ms
# Warmup Iteration   2: 6.443 ops/ms
# Warmup Iteration   3: 7.830 ops/ms
Iteration   1: 8.049 ops/ms
Iteration   2: 8.216 ops/ms
Iteration   3: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.203 ±(99.9%) 2.683 ops/ms [Average]
  (min, avg, max) = (8.049, 8.203, 8.343), stdev = 0.147
  CI (99.9%): [5.520, 10.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.030 ops/ms
# Warmup Iteration   2: 5.803 ops/ms
# Warmup Iteration   3: 6.448 ops/ms
Iteration   1: 6.539 ops/ms
Iteration   2: 6.911 ops/ms
Iteration   3: 7.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.838 ±(99.9%) 4.934 ops/ms [Average]
  (min, avg, max) = (6.539, 6.838, 7.065), stdev = 0.270
  CI (99.9%): [1.904, 11.772] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.066 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.007 ms/op
Iteration   1: 4.050 ±(99.9%) 0.004 ms/op
Iteration   2: 3.842 ±(99.9%) 0.012 ms/op
Iteration   3: 3.894 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.929 ±(99.9%) 1.974 ms/op [Average]
  (min, avg, max) = (3.842, 3.929, 4.050), stdev = 0.108
  CI (99.9%): [1.954, 5.903] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.424 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.006 ms/op
Iteration   1: 3.950 ±(99.9%) 0.009 ms/op
Iteration   2: 3.697 ±(99.9%) 0.008 ms/op
Iteration   3: 3.684 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.777 ±(99.9%) 2.736 ms/op [Average]
  (min, avg, max) = (3.684, 3.777, 3.950), stdev = 0.150
  CI (99.9%): [1.041, 6.513] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.592 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.775 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.008 ms/op
Iteration   1: 4.272 ±(99.9%) 0.011 ms/op
Iteration   2: 3.950 ±(99.9%) 0.006 ms/op
Iteration   3: 3.987 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.070 ±(99.9%) 3.213 ms/op [Average]
  (min, avg, max) = (3.950, 4.070, 4.272), stdev = 0.176
  CI (99.9%): [0.856, 7.283] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.021 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.514 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.979 ±(99.9%) 0.006 ms/op
Iteration   1: 4.785 ±(99.9%) 0.010 ms/op
Iteration   2: 4.675 ±(99.9%) 0.016 ms/op
Iteration   3: 4.830 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.763 ±(99.9%) 1.450 ms/op [Average]
  (min, avg, max) = (4.675, 4.763, 4.830), stdev = 0.079
  CI (99.9%): [3.313, 6.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.302 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.641 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.375 ±(99.9%) 0.019 ms/op
Iteration   1: 3.845 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  24.996 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   2: 3.856 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  24.872 ms/op
                 createUser·p0.9999: 28.277 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   3: 3.997 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.873 ms/op
                 createUser·p0.999:  16.499 ms/op
                 createUser·p0.9999: 31.752 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246127
  mean =      3.898 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 274 
    [ 2.500,  5.000) = 236892 
    [ 5.000,  7.500) = 6939 
    [ 7.500, 10.000) = 1393 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 153 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     24.502 ms/op
     p(99.9900) =     29.766 ms/op
     p(99.9990) =     33.413 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.421 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.909 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  13.426 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 3.968 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   7.890 ms/op
                 existUser·p0.999:  25.376 ms/op
                 existUser·p0.9999: 33.620 ms/op
                 existUser·p1.00:   34.079 ms/op

Iteration   3: 3.897 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  13.857 ms/op
                 existUser·p0.9999: 33.075 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244169
  mean =      3.930 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 321 
    [ 2.500,  5.000) = 231710 
    [ 5.000,  7.500) = 9747 
    [ 7.500, 10.000) = 1567 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 49 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.759 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.993 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     16.244 ms/op
     p(99.9900) =     33.036 ms/op
     p(99.9990) =     33.984 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.316 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.037 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.014 ms/op
Iteration   1: 4.154 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.610 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   6.300 ms/op
                 getUser·p0.99:   9.695 ms/op
                 getUser·p0.999:  24.043 ms/op
                 getUser·p0.9999: 29.304 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   2: 4.006 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.794 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  10.888 ms/op
                 getUser·p0.9999: 27.493 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.988 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.758 ms/op
                 getUser·p0.999:  28.599 ms/op
                 getUser·p0.9999: 32.144 ms/op
                 getUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237167
  mean =      4.048 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 238 
    [ 2.500,  5.000) = 220100 
    [ 5.000,  7.500) = 13586 
    [ 7.500, 10.000) = 2202 
    [10.000, 12.500) = 549 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     24.041 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     32.457 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.892 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 5.501 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.714 ±(99.9%) 0.019 ms/op
Iteration   1: 4.830 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  26.340 ms/op
                 listUser·p0.9999: 32.789 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   2: 4.669 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  17.995 ms/op
                 listUser·p0.9999: 22.189 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 4.601 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 18.779 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204154
  mean =      4.698 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 166892 
    [ 5.000,  7.500) = 32029 
    [ 7.500, 10.000) = 3831 
    [10.000, 12.500) = 765 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.802 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     30.319 ms/op
     p(99.9990) =     33.552 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.976 ± 9.482  ops/ms
ClientPb.existUser                       thrpt       3   8.434 ± 4.115  ops/ms
ClientPb.getUser                         thrpt       3   8.203 ± 2.683  ops/ms
ClientPb.listUser                        thrpt       3   6.838 ± 4.934  ops/ms
ClientPb.createUser                       avgt       3   3.929 ± 1.974   ms/op
ClientPb.existUser                        avgt       3   3.777 ± 2.736   ms/op
ClientPb.getUser                          avgt       3   4.070 ± 3.213   ms/op
ClientPb.listUser                         avgt       3   4.763 ± 1.450   ms/op
ClientPb.createUser                     sample  246127   3.898 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.676           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.086           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.502           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.766           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  244169   3.930 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.759           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.993           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.244           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.036           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.079           ms/op
ClientPb.getUser                        sample  237167   4.048 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.516           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.069           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.041           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.802           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.604           ms/op
ClientPb.listUser                       sample  204154   4.698 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.382           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.997           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.290           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.776           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.319           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.620           ms/op
