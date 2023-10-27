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
# Warmup Iteration   1: 1.737 ops/ms
# Warmup Iteration   2: 3.408 ops/ms
# Warmup Iteration   3: 7.129 ops/ms
Iteration   1: 7.547 ops/ms
Iteration   2: 7.650 ops/ms
Iteration   3: 7.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.655 ±(99.9%) 2.008 ops/ms [Average]
  (min, avg, max) = (7.547, 7.655, 7.767), stdev = 0.110
  CI (99.9%): [5.647, 9.663] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.037 ops/ms
# Warmup Iteration   2: 6.758 ops/ms
# Warmup Iteration   3: 7.999 ops/ms
Iteration   1: 8.131 ops/ms
Iteration   2: 8.183 ops/ms
Iteration   3: 8.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.128 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (8.071, 8.128, 8.183), stdev = 0.056
  CI (99.9%): [7.108, 9.149] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.982 ops/ms
# Warmup Iteration   2: 6.130 ops/ms
# Warmup Iteration   3: 7.708 ops/ms
Iteration   1: 8.205 ops/ms
Iteration   2: 7.891 ops/ms
Iteration   3: 8.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.049 ±(99.9%) 2.860 ops/ms [Average]
  (min, avg, max) = (7.891, 8.049, 8.205), stdev = 0.157
  CI (99.9%): [5.189, 10.909] (assumes normal distribution)


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
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 5.169 ops/ms
# Warmup Iteration   3: 6.251 ops/ms
Iteration   1: 6.464 ops/ms
Iteration   2: 6.566 ops/ms
Iteration   3: 6.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.547 ±(99.9%) 1.370 ops/ms [Average]
  (min, avg, max) = (6.464, 6.547, 6.610), stdev = 0.075
  CI (99.9%): [5.177, 7.917] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.713 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.160 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.265 ±(99.9%) 0.006 ms/op
Iteration   1: 4.227 ±(99.9%) 0.004 ms/op
Iteration   2: 4.237 ±(99.9%) 0.009 ms/op
Iteration   3: 4.105 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.190 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (4.105, 4.190, 4.237), stdev = 0.074
  CI (99.9%): [2.847, 5.532] (assumes normal distribution)


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
# Warmup Iteration   1: 10.695 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.005 ms/op
Iteration   1: 4.059 ±(99.9%) 0.004 ms/op
Iteration   2: 3.912 ±(99.9%) 0.005 ms/op
Iteration   3: 3.834 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.935 ±(99.9%) 2.082 ms/op [Average]
  (min, avg, max) = (3.834, 3.935, 4.059), stdev = 0.114
  CI (99.9%): [1.853, 6.017] (assumes normal distribution)


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
# Warmup Iteration   1: 13.700 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.079 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.004 ms/op
Iteration   1: 4.156 ±(99.9%) 0.003 ms/op
Iteration   2: 4.150 ±(99.9%) 0.005 ms/op
Iteration   3: 4.044 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.117 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (4.044, 4.117, 4.156), stdev = 0.063
  CI (99.9%): [2.959, 5.275] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 15.817 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.980 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.940 ±(99.9%) 0.007 ms/op
Iteration   1: 4.964 ±(99.9%) 0.010 ms/op
Iteration   2: 4.587 ±(99.9%) 0.013 ms/op
Iteration   3: 4.772 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.774 ±(99.9%) 3.439 ms/op [Average]
  (min, avg, max) = (4.587, 4.774, 4.964), stdev = 0.189
  CI (99.9%): [1.335, 8.213] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 13.076 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.879 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.016 ms/op
Iteration   1: 4.201 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   8.307 ms/op
                 createUser·p0.999:  24.248 ms/op
                 createUser·p0.9999: 27.157 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   2: 4.094 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.032 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.930 ms/op
                 createUser·p0.999:  13.189 ms/op
                 createUser·p0.9999: 31.404 ms/op
                 createUser·p1.00:   32.276 ms/op

Iteration   3: 4.255 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.855 ms/op
                 createUser·p0.50:   4.088 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  28.647 ms/op
                 createUser·p0.9999: 31.719 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229429
  mean =      4.182 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 249 
    [ 2.500,  5.000) = 212892 
    [ 5.000,  7.500) = 13247 
    [ 7.500, 10.000) = 2092 
    [10.000, 12.500) = 431 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     24.431 ms/op
     p(99.9900) =     31.395 ms/op
     p(99.9990) =     33.132 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 12.460 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.015 ms/op
Iteration   1: 3.943 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.884 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   6.893 ms/op
                 existUser·p0.999:  11.360 ms/op
                 existUser·p0.9999: 27.422 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 3.851 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  24.216 ms/op
                 existUser·p0.9999: 33.034 ms/op
                 existUser·p1.00:   33.620 ms/op

Iteration   3: 3.975 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  18.402 ms/op
                 existUser·p0.9999: 28.340 ms/op
                 existUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244545
  mean =      3.922 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190 
    [ 2.500,  5.000) = 233203 
    [ 5.000,  7.500) = 8713 
    [ 7.500, 10.000) = 1400 
    [10.000, 12.500) = 526 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 116 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     21.621 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     33.419 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 13.564 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.189 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.015 ms/op
Iteration   1: 4.115 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  24.257 ms/op
                 getUser·p0.9999: 27.276 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  11.846 ms/op
                 getUser·p0.9999: 27.599 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 4.036 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.815 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  27.125 ms/op
                 getUser·p0.9999: 31.760 ms/op
                 getUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235696
  mean =      4.071 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 222198 
    [ 5.000,  7.500) = 9612 
    [ 7.500, 10.000) = 2790 
    [10.000, 12.500) = 496 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 115 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     24.248 ms/op
     p(99.9900) =     30.147 ms/op
     p(99.9990) =     32.733 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 15.762 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.940 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.091 ±(99.9%) 0.018 ms/op
Iteration   1: 4.782 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.441 ms/op
                 listUser·p0.999:  25.035 ms/op
                 listUser·p0.9999: 27.742 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   2: 4.941 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.859 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  17.704 ms/op
                 listUser·p0.9999: 22.745 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   3: 5.154 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   7.520 ms/op
                 listUser·p0.99:   11.534 ms/op
                 listUser·p0.999:  18.678 ms/op
                 listUser·p0.9999: 23.940 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193661
  mean =      4.954 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 136165 
    [ 5.000,  7.500) = 51931 
    [ 7.500, 10.000) = 3712 
    [10.000, 12.500) = 833 
    [12.500, 15.000) = 431 
    [15.000, 17.500) = 278 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      2.150 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     28.779 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.655 ± 2.008  ops/ms
ClientPb.existUser                       thrpt       3   8.128 ± 1.021  ops/ms
ClientPb.getUser                         thrpt       3   8.049 ± 2.860  ops/ms
ClientPb.listUser                        thrpt       3   6.547 ± 1.370  ops/ms
ClientPb.createUser                       avgt       3   4.190 ± 1.343   ms/op
ClientPb.existUser                        avgt       3   3.935 ± 2.082   ms/op
ClientPb.getUser                          avgt       3   4.117 ± 1.158   ms/op
ClientPb.listUser                         avgt       3   4.774 ± 3.439   ms/op
ClientPb.createUser                     sample  229429   4.182 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.086           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.431           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.395           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  244545   3.922 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.116           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.496           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.621           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.097           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.620           ms/op
ClientPb.getUser                        sample  235696   4.071 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.368           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.634           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.248           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.147           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.997           ms/op
ClientPb.listUser                       sample  193661   4.954 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.150           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.863           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.857           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.066           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.901           ms/op
