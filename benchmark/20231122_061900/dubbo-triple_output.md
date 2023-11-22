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
# Warmup Iteration   1: 4.799 ops/ms
# Warmup Iteration   2: 12.155 ops/ms
# Warmup Iteration   3: 12.101 ops/ms
Iteration   1: 12.412 ops/ms
Iteration   2: 12.504 ops/ms
Iteration   3: 12.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.461 ±(99.9%) 0.848 ops/ms [Average]
  (min, avg, max) = (12.412, 12.461, 12.504), stdev = 0.046
  CI (99.9%): [11.613, 13.309] (assumes normal distribution)


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
# Warmup Iteration   1: 7.539 ops/ms
# Warmup Iteration   2: 13.005 ops/ms
# Warmup Iteration   3: 13.104 ops/ms
Iteration   1: 12.983 ops/ms
Iteration   2: 13.057 ops/ms
Iteration   3: 12.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.004 ±(99.9%) 0.854 ops/ms [Average]
  (min, avg, max) = (12.970, 13.004, 13.057), stdev = 0.047
  CI (99.9%): [12.149, 13.858] (assumes normal distribution)


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
# Warmup Iteration   1: 7.879 ops/ms
# Warmup Iteration   2: 12.223 ops/ms
# Warmup Iteration   3: 12.348 ops/ms
Iteration   1: 12.644 ops/ms
Iteration   2: 12.606 ops/ms
Iteration   3: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.583 ±(99.9%) 1.394 ops/ms [Average]
  (min, avg, max) = (12.497, 12.583, 12.644), stdev = 0.076
  CI (99.9%): [11.189, 13.976] (assumes normal distribution)


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
# Warmup Iteration   1: 6.799 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.571 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.544 ±(99.9%) 0.739 ops/ms [Average]
  (min, avg, max) = (10.497, 10.544, 10.571), stdev = 0.041
  CI (99.9%): [9.805, 11.283] (assumes normal distribution)


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (2.474, 2.505, 2.541), stdev = 0.034
  CI (99.9%): [1.894, 3.116] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.458, 2.469, 2.475), stdev = 0.009
  CI (99.9%): [2.299, 2.639] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
Iteration   1: 2.545 ±(99.9%) 0.004 ms/op
Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
Iteration   3: 2.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.546 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (2.543, 2.546, 2.550), stdev = 0.004
  CI (99.9%): [2.480, 2.613] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.004 ms/op
Iteration   1: 3.067 ±(99.9%) 0.007 ms/op
Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
Iteration   3: 3.039 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.040 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.015, 3.040, 3.067), stdev = 0.026
  CI (99.9%): [2.572, 3.508] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.378 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   4.026 ms/op
                 createUser·p0.999:  11.944 ms/op
                 createUser·p0.9999: 14.129 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  9.639 ms/op
                 createUser·p0.9999: 14.268 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  8.372 ms/op
                 createUser·p0.9999: 11.158 ms/op
                 createUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378039
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 178761 
    [ 2.500,  3.750) = 195004 
    [ 3.750,  5.000) = 3200 
    [ 5.000,  6.250) = 545 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.601 ms/op
     p(99.9900) =     13.815 ms/op
     p(99.9990) =     14.583 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.560 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.479 ms/op
                 existUser·p0.999:  5.647 ms/op
                 existUser·p0.9999: 13.418 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  7.547 ms/op
                 existUser·p0.9999: 12.975 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.957 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 11.256 ms/op
                 existUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389367
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 191590 
    [ 2.500,  3.750) = 190732 
    [ 3.750,  5.000) = 4445 
    [ 5.000,  6.250) = 1921 
    [ 6.250,  7.500) = 237 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.527 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     17.785 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  11.502 ms/op
                 getUser·p0.9999: 17.479 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.588 ms/op
                 getUser·p0.999:  9.329 ms/op
                 getUser·p0.9999: 16.349 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.641 ms/op
                 getUser·p0.9999: 10.899 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378908
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 185355 
    [ 2.500,  3.750) = 188452 
    [ 3.750,  5.000) = 3916 
    [ 5.000,  6.250) = 676 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.103 ms/op
     p(99.9900) =     16.125 ms/op
     p(99.9990) =     17.964 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.019 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.552 ms/op
                 listUser·p0.9999: 9.945 ms/op
                 listUser·p1.00:   10.994 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 12.681 ms/op
                 listUser·p1.00:   13.206 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 10.656 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317583
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 88430 
    [ 2.500,  3.750) = 189795 
    [ 3.750,  5.000) = 31948 
    [ 5.000,  6.250) = 5969 
    [ 6.250,  7.500) = 665 
    [ 7.500,  8.750) = 276 
    [ 8.750, 10.000) = 257 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.067 ms/op
     p(99.9900) =     11.173 ms/op
     p(99.9990) =     13.104 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.461 ± 0.848  ops/ms
ClientPb.existUser                       thrpt       3  13.004 ± 0.854  ops/ms
ClientPb.getUser                         thrpt       3  12.583 ± 1.394  ops/ms
ClientPb.listUser                        thrpt       3  10.544 ± 0.739  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.611   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.170   ms/op
ClientPb.getUser                          avgt       3   2.546 ± 0.066   ms/op
ClientPb.listUser                         avgt       3   3.040 ± 0.468   ms/op
ClientPb.createUser                     sample  378039   2.537 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.378           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.601           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.815           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  389367   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.690           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.527           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.055           ms/op
ClientPb.getUser                        sample  378908   2.532 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.871           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.103           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.125           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.481           ms/op
ClientPb.listUser                       sample  317583   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.067           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.173           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.206           ms/op
