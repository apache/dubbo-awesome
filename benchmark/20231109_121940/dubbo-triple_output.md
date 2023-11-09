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
# Warmup Iteration   1: 1.642 ops/ms
# Warmup Iteration   2: 4.694 ops/ms
# Warmup Iteration   3: 7.428 ops/ms
Iteration   1: 7.965 ops/ms
Iteration   2: 8.219 ops/ms
Iteration   3: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.065 ±(99.9%) 2.465 ops/ms [Average]
  (min, avg, max) = (7.965, 8.065, 8.219), stdev = 0.135
  CI (99.9%): [5.600, 10.530] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.348 ops/ms
# Warmup Iteration   2: 7.731 ops/ms
# Warmup Iteration   3: 8.189 ops/ms
Iteration   1: 8.899 ops/ms
Iteration   2: 8.716 ops/ms
Iteration   3: 8.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.814 ±(99.9%) 1.683 ops/ms [Average]
  (min, avg, max) = (8.716, 8.814, 8.899), stdev = 0.092
  CI (99.9%): [7.132, 10.497] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.317 ops/ms
# Warmup Iteration   2: 7.140 ops/ms
# Warmup Iteration   3: 8.086 ops/ms
Iteration   1: 8.099 ops/ms
Iteration   2: 8.565 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.346 ±(99.9%) 4.267 ops/ms [Average]
  (min, avg, max) = (8.099, 8.346, 8.565), stdev = 0.234
  CI (99.9%): [4.079, 12.613] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.227 ops/ms
# Warmup Iteration   2: 6.285 ops/ms
# Warmup Iteration   3: 7.035 ops/ms
Iteration   1: 6.879 ops/ms
Iteration   2: 7.290 ops/ms
Iteration   3: 7.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.188 ±(99.9%) 4.974 ops/ms [Average]
  (min, avg, max) = (6.879, 7.188, 7.394), stdev = 0.273
  CI (99.9%): [2.213, 12.162] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.355 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.006 ms/op
Iteration   1: 3.756 ±(99.9%) 0.004 ms/op
Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
Iteration   3: 3.867 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.770 ±(99.9%) 1.655 ms/op [Average]
  (min, avg, max) = (3.688, 3.770, 3.867), stdev = 0.091
  CI (99.9%): [2.115, 5.425] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.078 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.004 ms/op
Iteration   1: 3.706 ±(99.9%) 0.002 ms/op
Iteration   2: 3.712 ±(99.9%) 0.004 ms/op
Iteration   3: 3.828 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.749 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.706, 3.749, 3.828), stdev = 0.069
  CI (99.9%): [2.492, 5.006] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.306 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.004 ms/op
Iteration   1: 3.965 ±(99.9%) 0.004 ms/op
Iteration   2: 3.829 ±(99.9%) 0.003 ms/op
Iteration   3: 3.806 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.866 ±(99.9%) 1.570 ms/op [Average]
  (min, avg, max) = (3.806, 3.866, 3.965), stdev = 0.086
  CI (99.9%): [2.296, 5.437] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.793 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.131 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.732 ±(99.9%) 0.009 ms/op
Iteration   1: 4.604 ±(99.9%) 0.006 ms/op
Iteration   2: 4.662 ±(99.9%) 0.007 ms/op
Iteration   3: 4.709 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.658 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (4.604, 4.658, 4.709), stdev = 0.053
  CI (99.9%): [3.694, 5.622] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.776 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.016 ms/op
Iteration   1: 3.965 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  21.234 ms/op
                 createUser·p0.9999: 23.265 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 3.923 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  16.410 ms/op
                 createUser·p0.9999: 23.986 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 3.931 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.433 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  24.739 ms/op
                 createUser·p0.9999: 28.467 ms/op
                 createUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243503
  mean =      3.940 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 939 
    [ 2.500,  5.000) = 232165 
    [ 5.000,  7.500) = 8948 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     21.283 ms/op
     p(99.9900) =     27.338 ms/op
     p(99.9990) =     29.181 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.526 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.012 ms/op
Iteration   1: 3.725 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  13.107 ms/op
                 existUser·p0.9999: 25.397 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 3.979 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   9.126 ms/op
                 existUser·p0.999:  24.467 ms/op
                 existUser·p0.9999: 26.800 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   3: 3.818 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  8.937 ms/op
                 existUser·p0.9999: 31.154 ms/op
                 existUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250127
  mean =      3.838 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 492 
    [ 2.500,  5.000) = 238983 
    [ 5.000,  7.500) = 7726 
    [ 7.500, 10.000) = 2052 
    [10.000, 12.500) = 439 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     15.405 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     31.900 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.129 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.126 ±(99.9%) 0.016 ms/op
Iteration   1: 3.957 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   8.263 ms/op
                 getUser·p0.999:  19.169 ms/op
                 getUser·p0.9999: 28.273 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   2: 3.912 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.681 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  24.019 ms/op
                 getUser·p0.9999: 26.214 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 3.864 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  22.582 ms/op
                 getUser·p0.9999: 29.384 ms/op
                 getUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245436
  mean =      3.911 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 438 
    [ 2.500,  5.000) = 234388 
    [ 5.000,  7.500) = 8031 
    [ 7.500, 10.000) = 1775 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.583 ms/op
     p(99.9000) =     21.238 ms/op
     p(99.9900) =     28.538 ms/op
     p(99.9990) =     30.254 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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
# Warmup Iteration   1: 12.745 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.879 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.615 ±(99.9%) 0.016 ms/op
Iteration   1: 4.479 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  23.385 ms/op
                 listUser·p0.9999: 28.172 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   2: 4.555 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  16.559 ms/op
                 listUser·p0.9999: 19.626 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   3: 4.525 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212108
  mean =      4.520 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 189000 
    [ 5.000,  7.500) = 20308 
    [ 7.500, 10.000) = 1740 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 276 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      8.053 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     27.027 ms/op
     p(99.9990) =     28.369 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.065 ± 2.465  ops/ms
ClientPb.existUser                       thrpt       3   8.814 ± 1.683  ops/ms
ClientPb.getUser                         thrpt       3   8.346 ± 4.267  ops/ms
ClientPb.listUser                        thrpt       3   7.188 ± 4.974  ops/ms
ClientPb.createUser                       avgt       3   3.770 ± 1.655   ms/op
ClientPb.existUser                        avgt       3   3.749 ± 1.257   ms/op
ClientPb.getUser                          avgt       3   3.866 ± 1.570   ms/op
ClientPb.listUser                         avgt       3   4.658 ± 0.964   ms/op
ClientPb.createUser                     sample  243503   3.940 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.433           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.283           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.338           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.917           ms/op
ClientPb.existUser                      sample  250127   3.838 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.296           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.774           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.405           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.884           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.096           ms/op
ClientPb.getUser                        sample  245436   3.911 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.503           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.833           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.583           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.238           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.538           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.736           ms/op
ClientPb.listUser                       sample  212108   4.520 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.356           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.027           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.574           ms/op
