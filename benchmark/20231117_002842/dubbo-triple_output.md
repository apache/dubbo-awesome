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
# Warmup Iteration   1: 4.943 ops/ms
# Warmup Iteration   2: 11.971 ops/ms
# Warmup Iteration   3: 12.319 ops/ms
Iteration   1: 12.497 ops/ms
Iteration   2: 12.589 ops/ms
Iteration   3: 12.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.563 ±(99.9%) 1.055 ops/ms [Average]
  (min, avg, max) = (12.497, 12.563, 12.604), stdev = 0.058
  CI (99.9%): [11.509, 13.618] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.758 ops/ms
# Warmup Iteration   2: 12.752 ops/ms
# Warmup Iteration   3: 13.073 ops/ms
Iteration   1: 12.900 ops/ms
Iteration   2: 12.952 ops/ms
Iteration   3: 12.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.924 ±(99.9%) 0.478 ops/ms [Average]
  (min, avg, max) = (12.900, 12.924, 12.952), stdev = 0.026
  CI (99.9%): [12.446, 13.402] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.276 ops/ms
# Warmup Iteration   2: 12.152 ops/ms
# Warmup Iteration   3: 12.252 ops/ms
Iteration   1: 12.345 ops/ms
Iteration   2: 12.461 ops/ms
Iteration   3: 12.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.363 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (12.282, 12.363, 12.461), stdev = 0.091
  CI (99.9%): [10.711, 14.015] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.591 ops/ms
# Warmup Iteration   2: 10.131 ops/ms
# Warmup Iteration   3: 10.204 ops/ms
Iteration   1: 10.363 ops/ms
Iteration   2: 10.454 ops/ms
Iteration   3: 10.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.379 ±(99.9%) 1.248 ops/ms [Average]
  (min, avg, max) = (10.320, 10.379, 10.454), stdev = 0.068
  CI (99.9%): [9.131, 11.626] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.213 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.599 ±(99.9%) 0.005 ms/op
Iteration   1: 2.586 ±(99.9%) 0.004 ms/op
Iteration   2: 2.641 ±(99.9%) 0.004 ms/op
Iteration   3: 2.626 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.618 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (2.586, 2.618, 2.641), stdev = 0.029
  CI (99.9%): [2.096, 3.139] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.889 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.499 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (2.475, 2.499, 2.518), stdev = 0.021
  CI (99.9%): [2.108, 2.889] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.048 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.543 ±(99.9%) 0.005 ms/op
Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (2.533, 2.536, 2.543), stdev = 0.006
  CI (99.9%): [2.431, 2.641] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.717 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
Iteration   3: 3.031 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.030 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (3.024, 3.030, 3.035), stdev = 0.005
  CI (99.9%): [2.934, 3.127] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.490 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.653 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.589 ±(99.9%) 0.006 ms/op
Iteration   1: 2.581 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  12.786 ms/op
                 createUser·p0.9999: 14.370 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   2: 2.584 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  9.442 ms/op
                 createUser·p0.9999: 14.336 ms/op
                 createUser·p1.00:   15.417 ms/op

Iteration   3: 2.615 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   2.712 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   4.121 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 10.712 ms/op
                 createUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369761
  mean =      2.593 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 172576 
    [ 2.500,  3.750) = 192337 
    [ 3.750,  5.000) = 3886 
    [ 5.000,  6.250) = 490 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 82 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.683 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      8.605 ms/op
     p(99.9900) =     14.189 ms/op
     p(99.9990) =     15.322 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.757 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  12.801 ms/op
                 existUser·p0.9999: 14.565 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  8.960 ms/op
                 existUser·p0.9999: 13.946 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  9.172 ms/op
                 existUser·p0.9999: 13.294 ms/op
                 existUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381018
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 183013 
    [ 2.500,  3.750) = 193656 
    [ 3.750,  5.000) = 3340 
    [ 5.000,  6.250) = 503 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      9.027 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     14.898 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.056 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  11.772 ms/op
                 getUser·p0.9999: 17.336 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   3.984 ms/op
                 getUser·p0.999:  9.102 ms/op
                 getUser·p0.9999: 13.189 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  8.077 ms/op
                 getUser·p0.9999: 14.114 ms/op
                 getUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375294
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 181235 
    [ 2.500,  3.750) = 187751 
    [ 3.750,  5.000) = 4981 
    [ 5.000,  6.250) = 823 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     14.572 ms/op
     p(99.9990) =     17.948 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.637 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.009 ms/op
Iteration   1: 3.064 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.742 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.781 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   2: 3.066 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.829 ms/op
                 listUser·p0.999:  10.191 ms/op
                 listUser·p0.9999: 12.945 ms/op
                 listUser·p1.00:   14.123 ms/op

Iteration   3: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.691 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 10.757 ms/op
                 listUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312808
  mean =      3.066 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 85019 
    [ 2.500,  3.750) = 184762 
    [ 3.750,  5.000) = 34645 
    [ 5.000,  6.250) = 6745 
    [ 6.250,  7.500) = 841 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 274 
    [10.000, 11.250) = 185 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      9.604 ms/op
     p(99.9900) =     11.345 ms/op
     p(99.9990) =     13.838 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.563 ± 1.055  ops/ms
ClientPb.existUser                       thrpt       3  12.924 ± 0.478  ops/ms
ClientPb.getUser                         thrpt       3  12.363 ± 1.652  ops/ms
ClientPb.listUser                        thrpt       3  10.379 ± 1.248  ops/ms
ClientPb.createUser                       avgt       3   2.618 ± 0.522   ms/op
ClientPb.existUser                        avgt       3   2.499 ± 0.391   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.105   ms/op
ClientPb.listUser                         avgt       3   3.030 ± 0.096   ms/op
ClientPb.createUser                     sample  369761   2.593 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.823           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.683           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.605           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.189           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.417           ms/op
ClientPb.existUser                      sample  381018   2.517 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.049           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.601           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.027           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.090           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.483           ms/op
ClientPb.getUser                        sample  375294   2.556 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.039           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.618           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.572           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.416           ms/op
ClientPb.listUser                       sample  312808   3.066 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.691           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.604           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.345           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.123           ms/op
