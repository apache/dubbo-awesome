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
# Warmup Iteration   1: 5.067 ops/ms
# Warmup Iteration   2: 12.155 ops/ms
# Warmup Iteration   3: 12.405 ops/ms
Iteration   1: 12.802 ops/ms
Iteration   2: 12.799 ops/ms
Iteration   3: 12.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.785 ±(99.9%) 0.467 ops/ms [Average]
  (min, avg, max) = (12.756, 12.785, 12.802), stdev = 0.026
  CI (99.9%): [12.319, 13.252] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.596 ops/ms
# Warmup Iteration   2: 13.250 ops/ms
# Warmup Iteration   3: 13.309 ops/ms
Iteration   1: 13.225 ops/ms
Iteration   2: 13.438 ops/ms
Iteration   3: 13.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.295 ±(99.9%) 2.252 ops/ms [Average]
  (min, avg, max) = (13.223, 13.295, 13.438), stdev = 0.123
  CI (99.9%): [11.043, 15.547] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.653 ops/ms
# Warmup Iteration   2: 12.569 ops/ms
# Warmup Iteration   3: 12.751 ops/ms
Iteration   1: 12.760 ops/ms
Iteration   2: 12.839 ops/ms
Iteration   3: 12.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.855 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (12.760, 12.855, 12.965), stdev = 0.103
  CI (99.9%): [10.969, 14.740] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.970 ops/ms
# Warmup Iteration   2: 10.623 ops/ms
# Warmup Iteration   3: 10.680 ops/ms
Iteration   1: 10.643 ops/ms
Iteration   2: 10.673 ops/ms
Iteration   3: 10.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.648 ±(99.9%) 0.414 ops/ms [Average]
  (min, avg, max) = (10.629, 10.648, 10.673), stdev = 0.023
  CI (99.9%): [10.234, 11.062] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.497, 2.506, 2.514), stdev = 0.009
  CI (99.9%): [2.344, 2.667] (assumes normal distribution)


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
# Warmup Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.479 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.473, 2.479, 2.484), stdev = 0.005
  CI (99.9%): [2.382, 2.576] (assumes normal distribution)


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.003 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.491 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (2.461, 2.491, 2.507), stdev = 0.026
  CI (99.9%): [2.021, 2.960] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.602 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
Iteration   3: 3.020 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (3.017, 3.021, 3.026), stdev = 0.005
  CI (99.9%): [2.938, 3.104] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  10.972 ms/op
                 createUser·p0.9999: 14.270 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.457 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  7.195 ms/op
                 createUser·p0.9999: 9.902 ms/op
                 createUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383086
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 186114 
    [ 2.500,  3.750) = 193507 
    [ 3.750,  5.000) = 2679 
    [ 5.000,  6.250) = 296 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     14.425 ms/op
     p(99.9990) =     17.864 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.006 ms/op
Iteration   1: 2.451 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  6.742 ms/op
                 existUser·p0.9999: 16.232 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  6.323 ms/op
                 existUser·p0.9999: 14.306 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  7.642 ms/op
                 existUser·p0.9999: 11.847 ms/op
                 existUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388422
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 193187 
    [ 2.500,  3.750) = 191418 
    [ 3.750,  5.000) = 2904 
    [ 5.000,  6.250) = 441 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      6.473 ms/op
     p(99.9900) =     15.573 ms/op
     p(99.9990) =     16.371 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  6.844 ms/op
                 getUser·p0.9999: 13.782 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  8.128 ms/op
                 getUser·p0.9999: 11.570 ms/op
                 getUser·p1.00:   12.272 ms/op

Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 10.591 ms/op
                 getUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383226
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 188887 
    [ 2.500,  3.750) = 188223 
    [ 3.750,  5.000) = 4268 
    [ 5.000,  6.250) = 1334 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.181 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      7.878 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     13.932 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.009 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.674 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 12.738 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   2: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   12.026 ms/op

Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.639 ms/op
                 listUser·p0.999:  10.403 ms/op
                 listUser·p0.9999: 11.648 ms/op
                 listUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318950
  mean =      3.007 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 167 
    [ 1.250,  2.500) = 94906 
    [ 2.500,  3.750) = 184103 
    [ 3.750,  5.000) = 32091 
    [ 5.000,  6.250) = 6185 
    [ 6.250,  7.500) = 774 
    [ 7.500,  8.750) = 168 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 188 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.897 ms/op
     p(99.9900) =     12.108 ms/op
     p(99.9990) =     12.943 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.785 ± 0.467  ops/ms
ClientPb.existUser                       thrpt       3  13.295 ± 2.252  ops/ms
ClientPb.getUser                         thrpt       3  12.855 ± 1.885  ops/ms
ClientPb.listUser                        thrpt       3  10.648 ± 0.414  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.161   ms/op
ClientPb.existUser                        avgt       3   2.479 ± 0.097   ms/op
ClientPb.getUser                          avgt       3   2.491 ± 0.469   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.083   ms/op
ClientPb.createUser                     sample  383086   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.938           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.425           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.612           ms/op
ClientPb.existUser                      sample  388422   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.473           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.573           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.072           ms/op
ClientPb.getUser                        sample  383226   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.647           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.181           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.878           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.927           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.926           ms/op
ClientPb.listUser                       sample  318950   3.007 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.674           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.897           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.960           ms/op
