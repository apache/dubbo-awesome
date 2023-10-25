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
# Warmup Iteration   1: 1.746 ops/ms
# Warmup Iteration   2: 3.193 ops/ms
# Warmup Iteration   3: 6.985 ops/ms
Iteration   1: 6.899 ops/ms
Iteration   2: 7.208 ops/ms
Iteration   3: 7.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.049 ±(99.9%) 2.827 ops/ms [Average]
  (min, avg, max) = (6.899, 7.049, 7.208), stdev = 0.155
  CI (99.9%): [4.222, 9.876] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 6.137 ops/ms
# Warmup Iteration   3: 7.765 ops/ms
Iteration   1: 7.710 ops/ms
Iteration   2: 8.118 ops/ms
Iteration   3: 7.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.922 ±(99.9%) 3.730 ops/ms [Average]
  (min, avg, max) = (7.710, 7.922, 8.118), stdev = 0.204
  CI (99.9%): [4.192, 11.652] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.181 ops/ms
# Warmup Iteration   2: 5.942 ops/ms
# Warmup Iteration   3: 7.023 ops/ms
Iteration   1: 7.475 ops/ms
Iteration   2: 7.203 ops/ms
Iteration   3: 7.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.427 ±(99.9%) 3.719 ops/ms [Average]
  (min, avg, max) = (7.203, 7.427, 7.602), stdev = 0.204
  CI (99.9%): [3.708, 11.145] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.921 ops/ms
# Warmup Iteration   2: 5.174 ops/ms
# Warmup Iteration   3: 6.005 ops/ms
Iteration   1: 6.233 ops/ms
Iteration   2: 6.153 ops/ms
Iteration   3: 6.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.225 ±(99.9%) 1.256 ops/ms [Average]
  (min, avg, max) = (6.153, 6.225, 6.290), stdev = 0.069
  CI (99.9%): [4.969, 7.482] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 14.093 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.843 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.007 ms/op
Iteration   1: 4.210 ±(99.9%) 0.015 ms/op
Iteration   2: 4.149 ±(99.9%) 0.008 ms/op
Iteration   3: 4.098 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.152 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (4.098, 4.152, 4.210), stdev = 0.056
  CI (99.9%): [3.127, 5.178] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.264 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.006 ms/op
Iteration   1: 4.119 ±(99.9%) 0.004 ms/op
Iteration   2: 4.092 ±(99.9%) 0.006 ms/op
Iteration   3: 4.115 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.108 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (4.092, 4.108, 4.119), stdev = 0.015
  CI (99.9%): [3.841, 4.376] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.865 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.005 ms/op
Iteration   1: 4.324 ±(99.9%) 0.007 ms/op
Iteration   2: 4.106 ±(99.9%) 0.005 ms/op
Iteration   3: 3.979 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.136 ±(99.9%) 3.184 ms/op [Average]
  (min, avg, max) = (3.979, 4.136, 4.324), stdev = 0.175
  CI (99.9%): [0.952, 7.320] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.603 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.164 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.116 ±(99.9%) 0.008 ms/op
Iteration   1: 4.826 ±(99.9%) 0.008 ms/op
Iteration   2: 5.146 ±(99.9%) 0.006 ms/op
Iteration   3: 4.960 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.978 ±(99.9%) 2.932 ms/op [Average]
  (min, avg, max) = (4.826, 4.978, 5.146), stdev = 0.161
  CI (99.9%): [2.046, 7.909] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.912 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.494 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.447 ±(99.9%) 0.019 ms/op
Iteration   1: 4.043 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   7.775 ms/op
                 createUser·p0.999:  15.545 ms/op
                 createUser·p0.9999: 28.580 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   2: 4.224 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   7.651 ms/op
                 createUser·p0.999:  26.083 ms/op
                 createUser·p0.9999: 27.984 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   3: 4.145 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.837 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  12.932 ms/op
                 createUser·p0.9999: 33.245 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232028
  mean =      4.136 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 320 
    [ 2.500,  5.000) = 212551 
    [ 5.000,  7.500) = 16050 
    [ 7.500, 10.000) = 2230 
    [10.000, 12.500) = 502 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 115 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     15.791 ms/op
     p(99.9900) =     31.608 ms/op
     p(99.9990) =     33.380 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.585 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.080 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.015 ms/op
Iteration   1: 4.151 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.644 ms/op
                 existUser·p0.99:   7.954 ms/op
                 existUser·p0.999:  21.529 ms/op
                 existUser·p0.9999: 28.312 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   2: 4.183 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.997 ms/op
                 existUser·p0.99:   8.167 ms/op
                 existUser·p0.999:  13.303 ms/op
                 existUser·p0.9999: 28.749 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 4.140 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.403 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   9.734 ms/op
                 existUser·p0.999:  15.008 ms/op
                 existUser·p0.9999: 30.516 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 230852
  mean =      4.158 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 269 
    [ 2.500,  5.000) = 207250 
    [ 5.000,  7.500) = 19274 
    [ 7.500, 10.000) = 2855 
    [10.000, 12.500) = 803 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     15.321 ms/op
     p(99.9900) =     30.177 ms/op
     p(99.9990) =     31.034 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.038 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.473 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.614 ±(99.9%) 0.019 ms/op
Iteration   1: 4.412 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   9.241 ms/op
                 getUser·p0.999:  19.333 ms/op
                 getUser·p0.9999: 27.517 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   2: 4.152 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   7.971 ms/op
                 getUser·p0.999:  21.330 ms/op
                 getUser·p0.9999: 28.298 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   3: 4.442 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   4.071 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.595 ms/op
                 getUser·p0.99:   8.978 ms/op
                 getUser·p0.999:  30.699 ms/op
                 getUser·p0.9999: 33.219 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 221702
  mean =      4.332 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 192377 
    [ 5.000,  7.500) = 24283 
    [ 7.500, 10.000) = 3800 
    [10.000, 12.500) = 696 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      4.030 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     23.896 ms/op
     p(99.9900) =     32.358 ms/op
     p(99.9990) =     34.124 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 16.101 ±(99.9%) 0.263 ms/op
# Warmup Iteration   2: 6.372 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.383 ±(99.9%) 0.021 ms/op
Iteration   1: 5.195 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  24.296 ms/op
                 listUser·p0.9999: 27.422 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 5.359 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   5.087 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.512 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  24.982 ms/op
                 listUser·p0.9999: 27.923 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   3: 5.219 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  18.305 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 182352
  mean =      5.257 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 93614 
    [ 5.000,  7.500) = 80640 
    [ 7.500, 10.000) = 5926 
    [10.000, 12.500) = 1436 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     28.445 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.049 ± 2.827  ops/ms
ClientPb.existUser                       thrpt       3   7.922 ± 3.730  ops/ms
ClientPb.getUser                         thrpt       3   7.427 ± 3.719  ops/ms
ClientPb.listUser                        thrpt       3   6.225 ± 1.256  ops/ms
ClientPb.createUser                       avgt       3   4.152 ± 1.025   ms/op
ClientPb.existUser                        avgt       3   4.108 ± 0.268   ms/op
ClientPb.getUser                          avgt       3   4.136 ± 3.184   ms/op
ClientPb.listUser                         avgt       3   4.978 ± 2.932   ms/op
ClientPb.createUser                     sample  232028   4.136 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.524           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.012           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.791           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.608           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948           ms/op
ClientPb.existUser                      sample  230852   4.158 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.899           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.372           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.321           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.177           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.719           ms/op
ClientPb.getUser                        sample  221702   4.332 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.556           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.276           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.152           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.765           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.896           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.358           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  182352   5.257 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.524           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.095           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.338           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.627           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.623           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606           ms/op
