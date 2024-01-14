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
# Warmup Iteration   1: 4.661 ops/ms
# Warmup Iteration   2: 11.857 ops/ms
# Warmup Iteration   3: 12.021 ops/ms
Iteration   1: 12.377 ops/ms
Iteration   2: 12.332 ops/ms
Iteration   3: 12.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.381 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (12.332, 12.381, 12.435), stdev = 0.051
  CI (99.9%): [11.445, 13.318] (assumes normal distribution)


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
# Warmup Iteration   1: 7.841 ops/ms
# Warmup Iteration   2: 12.843 ops/ms
# Warmup Iteration   3: 12.873 ops/ms
Iteration   1: 12.791 ops/ms
Iteration   2: 12.872 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.828 ±(99.9%) 0.745 ops/ms [Average]
  (min, avg, max) = (12.791, 12.828, 12.872), stdev = 0.041
  CI (99.9%): [12.082, 13.573] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.373 ops/ms
# Warmup Iteration   2: 12.278 ops/ms
# Warmup Iteration   3: 12.696 ops/ms
Iteration   1: 12.708 ops/ms
Iteration   2: 12.551 ops/ms
Iteration   3: 12.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.658 ±(99.9%) 1.693 ops/ms [Average]
  (min, avg, max) = (12.551, 12.658, 12.714), stdev = 0.093
  CI (99.9%): [10.965, 14.350] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.505 ops/ms
# Warmup Iteration   2: 10.306 ops/ms
# Warmup Iteration   3: 10.355 ops/ms
Iteration   1: 10.395 ops/ms
Iteration   2: 10.295 ops/ms
Iteration   3: 10.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.352 ±(99.9%) 0.934 ops/ms [Average]
  (min, avg, max) = (10.295, 10.352, 10.395), stdev = 0.051
  CI (99.9%): [9.418, 11.286] (assumes normal distribution)


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.564 ±(99.9%) 0.004 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.567 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.558, 2.567, 2.577), stdev = 0.010
  CI (99.9%): [2.393, 2.741] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.483 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (2.463, 2.483, 2.496), stdev = 0.018
  CI (99.9%): [2.162, 2.803] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.003 ms/op
Iteration   1: 2.555 ±(99.9%) 0.004 ms/op
Iteration   2: 2.557 ±(99.9%) 0.004 ms/op
Iteration   3: 2.556 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.556 ±(99.9%) 0.013 ms/op [Average]
  (min, avg, max) = (2.555, 2.556, 2.557), stdev = 0.001
  CI (99.9%): [2.542, 2.569] (assumes normal distribution)


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
# Warmup Iteration   1: 4.891 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.114 ±(99.9%) 0.005 ms/op
Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
Iteration   3: 3.108 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.104 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (3.089, 3.104, 3.114), stdev = 0.013
  CI (99.9%): [2.861, 3.346] (assumes normal distribution)


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
# Warmup Iteration   1: 4.289 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.698 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.588 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  11.239 ms/op
                 createUser·p0.9999: 13.559 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.576 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  9.240 ms/op
                 createUser·p0.9999: 11.649 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   3: 2.586 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.997 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 12.118 ms/op
                 createUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371103
  mean =      2.583 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 175564 
    [ 2.500,  3.750) = 190663 
    [ 3.750,  5.000) = 3803 
    [ 5.000,  6.250) = 492 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 144 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      9.648 ms/op
     p(99.9900) =     13.233 ms/op
     p(99.9990) =     14.016 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.816 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.537 ms/op
                 existUser·p0.9999: 13.852 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  9.192 ms/op
                 existUser·p0.9999: 13.612 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  9.547 ms/op
                 existUser·p0.9999: 12.075 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381655
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 184751 
    [ 2.500,  3.750) = 193517 
    [ 3.750,  5.000) = 2604 
    [ 5.000,  6.250) = 348 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.326 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     14.503 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  11.850 ms/op
                 getUser·p0.9999: 16.165 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.355 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 13.337 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  7.976 ms/op
                 getUser·p0.9999: 11.963 ms/op
                 getUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379462
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 185390 
    [ 2.500,  3.750) = 186930 
    [ 3.750,  5.000) = 5286 
    [ 5.000,  6.250) = 1140 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     14.139 ms/op
     p(99.9990) =     16.981 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.009 ms/op
Iteration   1: 3.087 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  8.985 ms/op
                 listUser·p0.9999: 10.059 ms/op
                 listUser·p1.00:   10.338 ms/op

Iteration   2: 3.084 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.628 ms/op
                 listUser·p0.9999: 12.843 ms/op
                 listUser·p1.00:   13.320 ms/op

Iteration   3: 3.090 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.970 ms/op
                 listUser·p0.9999: 13.970 ms/op
                 listUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310738
  mean =      3.087 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 77852 
    [ 2.500,  3.750) = 187734 
    [ 3.750,  5.000) = 37138 
    [ 5.000,  6.250) = 6559 
    [ 6.250,  7.500) = 652 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 314 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.491 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     14.808 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.381 ± 0.937  ops/ms
ClientPb.existUser                       thrpt       3  12.828 ± 0.745  ops/ms
ClientPb.getUser                         thrpt       3  12.658 ± 1.693  ops/ms
ClientPb.listUser                        thrpt       3  10.352 ± 0.934  ops/ms
ClientPb.createUser                       avgt       3   2.567 ± 0.174   ms/op
ClientPb.existUser                        avgt       3   2.483 ± 0.320   ms/op
ClientPb.getUser                          avgt       3   2.556 ± 0.013   ms/op
ClientPb.listUser                         avgt       3   3.104 ± 0.242   ms/op
ClientPb.createUser                     sample  371103   2.583 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.954           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.648           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.233           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.451           ms/op
ClientPb.existUser                      sample  381655   2.513 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.902           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.605           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.326           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.550           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.582           ms/op
ClientPb.getUser                        sample  379462   2.528 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.880           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.568           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.139           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.138           ms/op
ClientPb.listUser                       sample  310738   3.087 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.491           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.861           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.828           ms/op
