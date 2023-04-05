# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.987 ops/ms
# Warmup Iteration   2: 2.453 ops/ms
# Warmup Iteration   3: 5.526 ops/ms
Iteration   1: 5.983 ops/ms
Iteration   2: 6.139 ops/ms
Iteration   3: 6.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.141 ±(99.9%) 2.901 ops/ms [Average]
  (min, avg, max) = (5.983, 6.141, 6.301), stdev = 0.159
  CI (99.9%): [3.239, 9.042] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.690 ops/ms
# Warmup Iteration   2: 4.799 ops/ms
# Warmup Iteration   3: 6.176 ops/ms
Iteration   1: 6.519 ops/ms
Iteration   2: 6.559 ops/ms
Iteration   3: 6.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.466 ±(99.9%) 2.326 ops/ms [Average]
  (min, avg, max) = (6.321, 6.466, 6.559), stdev = 0.127
  CI (99.9%): [4.141, 8.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.648 ops/ms
# Warmup Iteration   2: 4.550 ops/ms
# Warmup Iteration   3: 6.005 ops/ms
Iteration   1: 5.982 ops/ms
Iteration   2: 5.933 ops/ms
Iteration   3: 6.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.991 ±(99.9%) 1.148 ops/ms [Average]
  (min, avg, max) = (5.933, 5.991, 6.058), stdev = 0.063
  CI (99.9%): [4.843, 7.139] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.682 ops/ms
# Warmup Iteration   2: 4.219 ops/ms
# Warmup Iteration   3: 5.258 ops/ms
Iteration   1: 5.280 ops/ms
Iteration   2: 5.417 ops/ms
Iteration   3: 5.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.395 ±(99.9%) 1.925 ops/ms [Average]
  (min, avg, max) = (5.280, 5.395, 5.488), stdev = 0.106
  CI (99.9%): [3.470, 7.320] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.329 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.891 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.451 ±(99.9%) 0.009 ms/op
Iteration   1: 5.247 ±(99.9%) 0.013 ms/op
Iteration   2: 5.149 ±(99.9%) 0.011 ms/op
Iteration   3: 5.013 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.136 ±(99.9%) 2.145 ms/op [Average]
  (min, avg, max) = (5.013, 5.136, 5.247), stdev = 0.118
  CI (99.9%): [2.991, 7.281] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.296 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.473 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.982 ±(99.9%) 0.011 ms/op
Iteration   1: 4.877 ±(99.9%) 0.010 ms/op
Iteration   2: 4.924 ±(99.9%) 0.013 ms/op
Iteration   3: 4.778 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.860 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (4.778, 4.860, 4.924), stdev = 0.074
  CI (99.9%): [3.504, 6.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.726 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.098 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.358 ±(99.9%) 0.016 ms/op
Iteration   1: 5.116 ±(99.9%) 0.021 ms/op
Iteration   2: 5.225 ±(99.9%) 0.016 ms/op
Iteration   3: 5.328 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.223 ±(99.9%) 1.935 ms/op [Average]
  (min, avg, max) = (5.116, 5.223, 5.328), stdev = 0.106
  CI (99.9%): [3.288, 7.158] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.839 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 7.945 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.119 ±(99.9%) 0.011 ms/op
Iteration   1: 5.985 ±(99.9%) 0.015 ms/op
Iteration   2: 6.137 ±(99.9%) 0.016 ms/op
Iteration   3: 5.589 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.904 ±(99.9%) 5.161 ms/op [Average]
  (min, avg, max) = (5.589, 5.904, 6.137), stdev = 0.283
  CI (99.9%): [0.743, 11.064] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.674 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.226 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.616 ±(99.9%) 0.025 ms/op
Iteration   1: 5.389 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.685 ms/op
                 createUser·p0.95:   7.660 ms/op
                 createUser·p0.99:   10.627 ms/op
                 createUser·p0.999:  22.348 ms/op
                 createUser·p0.9999: 27.217 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   2: 5.125 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   4.891 ms/op
                 createUser·p0.90:   6.136 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   9.454 ms/op
                 createUser·p0.999:  24.832 ms/op
                 createUser·p0.9999: 28.609 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 4.999 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   4.743 ms/op
                 createUser·p0.90:   5.898 ms/op
                 createUser·p0.95:   7.201 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  25.236 ms/op
                 createUser·p0.9999: 32.062 ms/op
                 createUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185622
  mean =      5.166 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 109604 
    [ 5.000,  7.500) = 68027 
    [ 7.500, 10.000) = 5984 
    [10.000, 12.500) = 1233 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     23.147 ms/op
     p(99.9900) =     31.019 ms/op
     p(99.9990) =     32.675 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.577 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.853 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.116 ±(99.9%) 0.018 ms/op
Iteration   1: 4.960 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   5.906 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  21.100 ms/op
                 existUser·p0.9999: 30.933 ms/op
                 existUser·p1.00:   33.030 ms/op

Iteration   2: 5.004 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   4.743 ms/op
                 existUser·p0.90:   5.997 ms/op
                 existUser·p0.95:   6.948 ms/op
                 existUser·p0.99:   9.896 ms/op
                 existUser·p0.999:  29.464 ms/op
                 existUser·p0.9999: 36.257 ms/op
                 existUser·p1.00:   37.224 ms/op

Iteration   3: 4.955 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.676 ms/op
                 existUser·p0.99:   8.910 ms/op
                 existUser·p0.999:  20.979 ms/op
                 existUser·p0.9999: 29.378 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 192791
  mean =      4.973 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 131558 
    [ 5.000,  7.500) = 55270 
    [ 7.500, 10.000) = 4374 
    [10.000, 12.500) = 1034 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     18.691 ms/op
     p(99.9900) =     34.126 ms/op
     p(99.9990) =     36.677 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.716 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 6.326 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.476 ±(99.9%) 0.023 ms/op
Iteration   1: 5.273 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.792 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.160 ms/op
                 getUser·p0.95:   7.684 ms/op
                 getUser·p0.99:   11.436 ms/op
                 getUser·p0.999:  21.356 ms/op
                 getUser·p0.9999: 25.033 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   2: 5.160 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.433 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   6.881 ms/op
                 getUser·p0.99:   10.174 ms/op
                 getUser·p0.999:  21.594 ms/op
                 getUser·p0.9999: 25.035 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 5.203 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.396 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.291 ms/op
                 getUser·p0.95:   7.496 ms/op
                 getUser·p0.99:   10.256 ms/op
                 getUser·p0.999:  21.708 ms/op
                 getUser·p0.9999: 26.583 ms/op
                 getUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184100
  mean =      5.212 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 102161 
    [ 5.000,  7.500) = 73158 
    [ 7.500, 10.000) = 6272 
    [10.000, 12.500) = 1464 
    [12.500, 15.000) = 566 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.792 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      7.405 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     27.353 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.481 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 7.714 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.228 ±(99.9%) 0.024 ms/op
Iteration   1: 6.169 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.941 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   9.372 ms/op
                 listUser·p0.99:   13.025 ms/op
                 listUser·p0.999:  25.595 ms/op
                 listUser·p0.9999: 27.807 ms/op
                 listUser·p1.00:   29.753 ms/op

Iteration   2: 5.931 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.151 ms/op
                 listUser·p0.99:   10.863 ms/op
                 listUser·p0.999:  28.246 ms/op
                 listUser·p0.9999: 30.022 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   3: 5.956 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  20.935 ms/op
                 listUser·p0.9999: 26.461 ms/op
                 listUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159585
  mean =      6.017 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 11539 
    [ 5.000,  7.500) = 134074 
    [ 7.500, 10.000) = 9594 
    [10.000, 12.500) = 2852 
    [12.500, 15.000) = 768 
    [15.000, 17.500) = 298 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.021 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      7.258 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     12.354 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     29.427 ms/op
     p(99.9990) =     30.948 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.141 ± 2.901  ops/ms
ClientPb.existUser                       thrpt       3   6.466 ± 2.326  ops/ms
ClientPb.getUser                         thrpt       3   5.991 ± 1.148  ops/ms
ClientPb.listUser                        thrpt       3   5.395 ± 1.925  ops/ms
ClientPb.createUser                       avgt       3   5.136 ± 2.145   ms/op
ClientPb.existUser                        avgt       3   4.860 ± 1.356   ms/op
ClientPb.getUser                          avgt       3   5.223 ± 1.935   ms/op
ClientPb.listUser                         avgt       3   5.904 ± 5.161   ms/op
ClientPb.createUser                     sample  185622   5.166 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.031           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.300           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.125           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.147           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.019           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.096           ms/op
ClientPb.existUser                      sample  192791   4.973 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.647           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.568           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.691           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.126           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.224           ms/op
ClientPb.getUser                        sample  184100   5.212 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.792           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.923           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.405           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.764           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.496           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.625           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.656           ms/op
ClientPb.listUser                       sample  159585   6.017 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.021           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.354           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.625           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.427           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.162           ms/op
