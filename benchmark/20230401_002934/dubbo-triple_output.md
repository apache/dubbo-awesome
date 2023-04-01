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
# Warmup Iteration   1: 1.076 ops/ms
# Warmup Iteration   2: 2.686 ops/ms
# Warmup Iteration   3: 5.025 ops/ms
Iteration   1: 5.393 ops/ms
Iteration   2: 5.567 ops/ms
Iteration   3: 5.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.639 ±(99.9%) 5.272 ops/ms [Average]
  (min, avg, max) = (5.393, 5.639, 5.957), stdev = 0.289
  CI (99.9%): [0.367, 10.910] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.594 ops/ms
# Warmup Iteration   2: 4.907 ops/ms
# Warmup Iteration   3: 6.029 ops/ms
Iteration   1: 6.188 ops/ms
Iteration   2: 6.336 ops/ms
Iteration   3: 6.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.288 ±(99.9%) 1.583 ops/ms [Average]
  (min, avg, max) = (6.188, 6.288, 6.341), stdev = 0.087
  CI (99.9%): [4.705, 7.871] (assumes normal distribution)


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
# Warmup Iteration   1: 1.734 ops/ms
# Warmup Iteration   2: 4.693 ops/ms
# Warmup Iteration   3: 5.668 ops/ms
Iteration   1: 5.938 ops/ms
Iteration   2: 6.057 ops/ms
Iteration   3: 5.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.873 ±(99.9%) 4.087 ops/ms [Average]
  (min, avg, max) = (5.623, 5.873, 6.057), stdev = 0.224
  CI (99.9%): [1.785, 9.960] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.493 ops/ms
# Warmup Iteration   2: 3.870 ops/ms
# Warmup Iteration   3: 4.918 ops/ms
Iteration   1: 5.050 ops/ms
Iteration   2: 4.997 ops/ms
Iteration   3: 4.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.891 ±(99.9%) 4.205 ops/ms [Average]
  (min, avg, max) = (4.627, 4.891, 5.050), stdev = 0.231
  CI (99.9%): [0.686, 9.096] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.007 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 6.631 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.760 ±(99.9%) 0.016 ms/op
Iteration   1: 5.529 ±(99.9%) 0.012 ms/op
Iteration   2: 5.355 ±(99.9%) 0.014 ms/op
Iteration   3: 5.592 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.492 ±(99.9%) 2.239 ms/op [Average]
  (min, avg, max) = (5.355, 5.492, 5.592), stdev = 0.123
  CI (99.9%): [3.253, 7.731] (assumes normal distribution)


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
# Warmup Iteration   1: 17.177 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.875 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.439 ±(99.9%) 0.008 ms/op
Iteration   1: 5.412 ±(99.9%) 0.015 ms/op
Iteration   2: 5.052 ±(99.9%) 0.022 ms/op
Iteration   3: 5.288 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.251 ±(99.9%) 3.336 ms/op [Average]
  (min, avg, max) = (5.052, 5.251, 5.412), stdev = 0.183
  CI (99.9%): [1.914, 8.587] (assumes normal distribution)


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
# Warmup Iteration   1: 17.184 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 7.484 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.479 ±(99.9%) 0.009 ms/op
Iteration   1: 5.542 ±(99.9%) 0.011 ms/op
Iteration   2: 5.514 ±(99.9%) 0.012 ms/op
Iteration   3: 5.321 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.459 ±(99.9%) 2.191 ms/op [Average]
  (min, avg, max) = (5.321, 5.459, 5.542), stdev = 0.120
  CI (99.9%): [3.268, 7.650] (assumes normal distribution)


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
# Warmup Iteration   1: 18.344 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 8.047 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.461 ±(99.9%) 0.010 ms/op
Iteration   1: 6.493 ±(99.9%) 0.013 ms/op
Iteration   2: 6.251 ±(99.9%) 0.016 ms/op
Iteration   3: 6.522 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.422 ±(99.9%) 2.715 ms/op [Average]
  (min, avg, max) = (6.251, 6.422, 6.522), stdev = 0.149
  CI (99.9%): [3.706, 9.137] (assumes normal distribution)


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
# Warmup Iteration   1: 16.795 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.842 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.540 ±(99.9%) 0.032 ms/op
Iteration   1: 5.481 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.372 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.668 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  24.163 ms/op
                 createUser·p0.9999: 28.514 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   2: 5.537 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.449 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.758 ms/op
                 createUser·p0.95:   7.791 ms/op
                 createUser·p0.99:   11.354 ms/op
                 createUser·p0.999:  21.234 ms/op
                 createUser·p0.9999: 33.817 ms/op
                 createUser·p1.00:   34.669 ms/op

Iteration   3: 5.672 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   6.775 ms/op
                 createUser·p0.95:   7.660 ms/op
                 createUser·p0.99:   10.404 ms/op
                 createUser·p0.999:  28.388 ms/op
                 createUser·p0.9999: 32.599 ms/op
                 createUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172407
  mean =      5.562 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 59488 
    [ 5.000,  7.500) = 103298 
    [ 7.500, 10.000) = 7300 
    [10.000, 12.500) = 1471 
    [12.500, 15.000) = 461 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.758 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.517 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     33.098 ms/op
     p(99.9990) =     34.241 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.091 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 6.812 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.285 ±(99.9%) 0.017 ms/op
Iteration   1: 5.406 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.742 ms/op
                 existUser·p0.95:   7.823 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  24.669 ms/op
                 existUser·p0.9999: 28.096 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   2: 5.260 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.499 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.594 ms/op
                 existUser·p0.99:   10.568 ms/op
                 existUser·p0.999:  16.240 ms/op
                 existUser·p0.9999: 30.693 ms/op
                 existUser·p1.00:   30.933 ms/op

Iteration   3: 5.209 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.398 ms/op
                 existUser·p0.95:   7.250 ms/op
                 existUser·p0.99:   9.617 ms/op
                 existUser·p0.999:  28.486 ms/op
                 existUser·p0.9999: 33.856 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181287
  mean =      5.290 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 98208 
    [ 5.000,  7.500) = 73843 
    [ 7.500, 10.000) = 6984 
    [10.000, 12.500) = 1349 
    [12.500, 15.000) = 458 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.528 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     19.974 ms/op
     p(99.9900) =     31.289 ms/op
     p(99.9990) =     34.140 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 17.083 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 6.922 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.916 ±(99.9%) 0.022 ms/op
Iteration   1: 5.721 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.703 ms/op
                 getUser·p0.50:   5.431 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   8.151 ms/op
                 getUser·p0.99:   11.764 ms/op
                 getUser·p0.999:  16.089 ms/op
                 getUser·p0.9999: 28.941 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   2: 5.632 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   7.930 ms/op
                 getUser·p0.99:   10.666 ms/op
                 getUser·p0.999:  28.246 ms/op
                 getUser·p0.9999: 31.304 ms/op
                 getUser·p1.00:   33.063 ms/op

Iteration   3: 5.685 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   3.006 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.651 ms/op
                 getUser·p0.99:   11.403 ms/op
                 getUser·p0.999:  28.813 ms/op
                 getUser·p0.9999: 32.810 ms/op
                 getUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169113
  mean =      5.679 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 45139 
    [ 5.000,  7.500) = 113635 
    [ 7.500, 10.000) = 7497 
    [10.000, 12.500) = 1772 
    [12.500, 15.000) = 676 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     11.270 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     31.871 ms/op
     p(99.9990) =     33.333 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 20.834 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 8.613 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 7.001 ±(99.9%) 0.033 ms/op
Iteration   1: 6.708 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   8.069 ms/op
                 listUser·p0.95:   9.650 ms/op
                 listUser·p0.99:   13.631 ms/op
                 listUser·p0.999:  28.446 ms/op
                 listUser·p0.9999: 48.824 ms/op
                 listUser·p1.00:   51.380 ms/op

Iteration   2: 6.589 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.878 ms/op
                 listUser·p0.999:  27.966 ms/op
                 listUser·p0.9999: 30.863 ms/op
                 listUser·p1.00:   32.244 ms/op

Iteration   3: 6.581 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.699 ms/op
                 listUser·p0.50:   6.103 ms/op
                 listUser·p0.90:   8.266 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   13.093 ms/op
                 listUser·p0.999:  27.898 ms/op
                 listUser·p0.9999: 32.679 ms/op
                 listUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144717
  mean =      6.626 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3278 
    [ 5.000, 10.000) = 135967 
    [10.000, 15.000) = 4639 
    [15.000, 20.000) = 477 
    [20.000, 25.000) = 74 
    [25.000, 30.000) = 213 
    [30.000, 35.000) = 38 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 24 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.023 ms/op
     p(50.0000) =      6.218 ms/op
     p(90.0000) =      7.995 ms/op
     p(95.0000) =      9.372 ms/op
     p(99.0000) =     12.878 ms/op
     p(99.9000) =     28.091 ms/op
     p(99.9900) =     44.009 ms/op
     p(99.9990) =     50.501 ms/op
     p(99.9999) =     51.380 ms/op
    p(100.0000) =     51.380 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.639 ± 5.272  ops/ms
ClientPb.existUser                       thrpt       3   6.288 ± 1.583  ops/ms
ClientPb.getUser                         thrpt       3   5.873 ± 4.087  ops/ms
ClientPb.listUser                        thrpt       3   4.891 ± 4.205  ops/ms
ClientPb.createUser                       avgt       3   5.492 ± 2.239   ms/op
ClientPb.existUser                        avgt       3   5.251 ± 3.336   ms/op
ClientPb.getUser                          avgt       3   5.459 ± 2.191   ms/op
ClientPb.listUser                         avgt       3   6.422 ± 2.715   ms/op
ClientPb.createUser                     sample  172407   5.562 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.314           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.758           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.700           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.517           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.098           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.669           ms/op
ClientPb.existUser                      sample  181287   5.290 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.155           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.528           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.502           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.974           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.289           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.406           ms/op
ClientPb.getUser                        sample  169113   5.679 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.363           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.922           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.270           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.168           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.871           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.423           ms/op
ClientPb.listUser                       sample  144717   6.626 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.023           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.218           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.995           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.372           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.878           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.091           ms/op
ClientPb.listUser:listUser·p0.9999      sample          44.009           ms/op
ClientPb.listUser:listUser·p1.00        sample          51.380           ms/op
