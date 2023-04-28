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
# Warmup Iteration   1: 1.456 ops/ms
# Warmup Iteration   2: 3.664 ops/ms
# Warmup Iteration   3: 7.064 ops/ms
Iteration   1: 7.597 ops/ms
Iteration   2: 7.622 ops/ms
Iteration   3: 7.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.535 ±(99.9%) 2.377 ops/ms [Average]
  (min, avg, max) = (7.385, 7.535, 7.622), stdev = 0.130
  CI (99.9%): [5.158, 9.912] (assumes normal distribution)


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
# Warmup Iteration   1: 2.132 ops/ms
# Warmup Iteration   2: 6.270 ops/ms
# Warmup Iteration   3: 7.917 ops/ms
Iteration   1: 8.365 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.244 ±(99.9%) 3.111 ops/ms [Average]
  (min, avg, max) = (8.049, 8.244, 8.365), stdev = 0.171
  CI (99.9%): [5.133, 11.355] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.016 ops/ms
# Warmup Iteration   2: 6.437 ops/ms
# Warmup Iteration   3: 8.165 ops/ms
Iteration   1: 7.637 ops/ms
Iteration   2: 7.965 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.798 ±(99.9%) 2.988 ops/ms [Average]
  (min, avg, max) = (7.637, 7.798, 7.965), stdev = 0.164
  CI (99.9%): [4.809, 10.786] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.072 ops/ms
# Warmup Iteration   2: 5.448 ops/ms
# Warmup Iteration   3: 6.772 ops/ms
Iteration   1: 6.477 ops/ms
Iteration   2: 6.489 ops/ms
Iteration   3: 6.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.558 ±(99.9%) 2.374 ops/ms [Average]
  (min, avg, max) = (6.477, 6.558, 6.708), stdev = 0.130
  CI (99.9%): [4.184, 8.932] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.168 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.653 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.006 ms/op
Iteration   1: 4.027 ±(99.9%) 0.008 ms/op
Iteration   2: 4.240 ±(99.9%) 0.008 ms/op
Iteration   3: 4.113 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.127 ±(99.9%) 1.949 ms/op [Average]
  (min, avg, max) = (4.027, 4.127, 4.240), stdev = 0.107
  CI (99.9%): [2.177, 6.076] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.246 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.002 ms/op
Iteration   1: 3.872 ±(99.9%) 0.009 ms/op
Iteration   2: 3.799 ±(99.9%) 0.006 ms/op
Iteration   3: 4.020 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.897 ±(99.9%) 2.052 ms/op [Average]
  (min, avg, max) = (3.799, 3.897, 4.020), stdev = 0.112
  CI (99.9%): [1.845, 5.949] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.808 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.464 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.008 ms/op
Iteration   1: 4.205 ±(99.9%) 0.005 ms/op
Iteration   2: 4.127 ±(99.9%) 0.005 ms/op
Iteration   3: 4.045 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.126 ±(99.9%) 1.462 ms/op [Average]
  (min, avg, max) = (4.045, 4.126, 4.205), stdev = 0.080
  CI (99.9%): [2.664, 5.587] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.284 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.612 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.219 ±(99.9%) 0.008 ms/op
Iteration   1: 5.069 ±(99.9%) 0.007 ms/op
Iteration   2: 4.785 ±(99.9%) 0.016 ms/op
Iteration   3: 4.816 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.890 ±(99.9%) 2.840 ms/op [Average]
  (min, avg, max) = (4.785, 4.890, 5.069), stdev = 0.156
  CI (99.9%): [2.050, 7.729] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.754 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 5.758 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.465 ±(99.9%) 0.019 ms/op
Iteration   1: 4.054 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.749 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   8.348 ms/op
                 createUser·p0.999:  23.730 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.054 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.617 ms/op
                 createUser·p0.999:  14.385 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 4.303 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.028 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  30.081 ms/op
                 createUser·p0.9999: 32.047 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235019
  mean =      4.081 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183 
    [ 2.500,  5.000) = 218043 
    [ 5.000,  7.500) = 13071 
    [ 7.500, 10.000) = 2704 
    [10.000, 12.500) = 530 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 75 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     24.148 ms/op
     p(99.9900) =     31.211 ms/op
     p(99.9990) =     32.317 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.637 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.016 ms/op
Iteration   1: 4.077 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.841 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   8.274 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 27.891 ms/op
                 existUser·p1.00:   28.639 ms/op

Iteration   2: 3.889 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   5.002 ms/op
                 existUser·p0.99:   7.813 ms/op
                 existUser·p0.999:  12.432 ms/op
                 existUser·p0.9999: 27.733 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 3.958 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.876 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   7.426 ms/op
                 existUser·p0.999:  28.942 ms/op
                 existUser·p0.9999: 32.208 ms/op
                 existUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241413
  mean =      3.973 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 278 
    [ 2.500,  5.000) = 225305 
    [ 5.000,  7.500) = 12719 
    [ 7.500, 10.000) = 2347 
    [10.000, 12.500) = 495 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.577 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     14.489 ms/op
     p(99.9900) =     31.317 ms/op
     p(99.9990) =     33.095 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 13.497 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.084 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.014 ms/op
Iteration   1: 4.093 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  24.669 ms/op
                 getUser·p0.9999: 31.863 ms/op
                 getUser·p1.00:   32.375 ms/op

Iteration   2: 4.053 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.506 ms/op
                 getUser·p0.999:  20.189 ms/op
                 getUser·p0.9999: 29.204 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   3: 4.171 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  15.712 ms/op
                 getUser·p0.9999: 28.781 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233687
  mean =      4.105 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 218985 
    [ 5.000,  7.500) = 11089 
    [ 7.500, 10.000) = 2600 
    [10.000, 12.500) = 427 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     23.722 ms/op
     p(99.9900) =     30.193 ms/op
     p(99.9990) =     32.265 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 15.452 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.963 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.163 ±(99.9%) 0.020 ms/op
Iteration   1: 5.080 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   7.389 ms/op
                 listUser·p0.99:   10.607 ms/op
                 listUser·p0.999:  24.253 ms/op
                 listUser·p0.9999: 26.102 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   2: 4.662 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.888 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  18.753 ms/op
                 listUser·p0.9999: 25.211 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   3: 4.824 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197791
  mean =      4.849 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 160265 
    [ 5.000,  7.500) = 31331 
    [ 7.500, 10.000) = 4547 
    [10.000, 12.500) = 870 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     20.559 ms/op
     p(99.9900) =     25.534 ms/op
     p(99.9990) =     26.548 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.535 ± 2.377  ops/ms
ClientPb.existUser                       thrpt       3   8.244 ± 3.111  ops/ms
ClientPb.getUser                         thrpt       3   7.798 ± 2.988  ops/ms
ClientPb.listUser                        thrpt       3   6.558 ± 2.374  ops/ms
ClientPb.createUser                       avgt       3   4.127 ± 1.949   ms/op
ClientPb.existUser                        avgt       3   3.897 ± 2.052   ms/op
ClientPb.getUser                          avgt       3   4.126 ± 1.462   ms/op
ClientPb.listUser                         avgt       3   4.890 ± 2.840   ms/op
ClientPb.createUser                     sample  235019   4.081 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.749           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.143           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.148           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.211           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.997           ms/op
ClientPb.existUser                      sample  241413   3.973 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.577           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.954           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.489           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.317           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.522           ms/op
ClientPb.getUser                        sample  233687   4.105 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.362           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.110           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.722           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.193           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.375           ms/op
ClientPb.listUser                       sample  197791   4.849 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.398           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.559           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.534           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.804           ms/op
