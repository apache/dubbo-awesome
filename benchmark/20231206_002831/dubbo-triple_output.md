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
# Warmup Iteration   1: 4.961 ops/ms
# Warmup Iteration   2: 12.303 ops/ms
# Warmup Iteration   3: 12.644 ops/ms
Iteration   1: 12.883 ops/ms
Iteration   2: 12.877 ops/ms
Iteration   3: 12.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.917 ±(99.9%) 1.179 ops/ms [Average]
  (min, avg, max) = (12.877, 12.917, 12.992), stdev = 0.065
  CI (99.9%): [11.738, 14.097] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.595 ops/ms
# Warmup Iteration   2: 13.281 ops/ms
# Warmup Iteration   3: 13.459 ops/ms
Iteration   1: 13.442 ops/ms
Iteration   2: 13.527 ops/ms
Iteration   3: 13.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.460 ±(99.9%) 1.093 ops/ms [Average]
  (min, avg, max) = (13.411, 13.460, 13.527), stdev = 0.060
  CI (99.9%): [12.367, 14.552] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.086 ops/ms
# Warmup Iteration   2: 12.728 ops/ms
# Warmup Iteration   3: 12.971 ops/ms
Iteration   1: 12.973 ops/ms
Iteration   2: 13.033 ops/ms
Iteration   3: 12.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.946 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (12.833, 12.946, 13.033), stdev = 0.103
  CI (99.9%): [11.074, 14.818] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.193 ops/ms
# Warmup Iteration   2: 10.684 ops/ms
# Warmup Iteration   3: 10.766 ops/ms
Iteration   1: 10.783 ops/ms
Iteration   2: 10.826 ops/ms
Iteration   3: 10.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.821 ±(99.9%) 0.656 ops/ms [Average]
  (min, avg, max) = (10.783, 10.821, 10.855), stdev = 0.036
  CI (99.9%): [10.165, 11.478] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.003 ms/op
Iteration   1: 2.465 ±(99.9%) 0.003 ms/op
Iteration   2: 2.483 ±(99.9%) 0.003 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.490 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (2.465, 2.490, 2.522), stdev = 0.030
  CI (99.9%): [1.952, 3.028] (assumes normal distribution)


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
# Warmup Iteration   1: 3.503 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.411 ±(99.9%) 0.005 ms/op
Iteration   1: 2.400 ±(99.9%) 0.004 ms/op
Iteration   2: 2.406 ±(99.9%) 0.003 ms/op
Iteration   3: 2.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.402 ±(99.9%) 0.064 ms/op [Average]
  (min, avg, max) = (2.399, 2.402, 2.406), stdev = 0.004
  CI (99.9%): [2.338, 2.466] (assumes normal distribution)


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.465 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.448, 2.465, 2.478), stdev = 0.015
  CI (99.9%): [2.193, 2.737] (assumes normal distribution)


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.006 ms/op
Iteration   1: 2.949 ±(99.9%) 0.005 ms/op
Iteration   2: 2.939 ±(99.9%) 0.005 ms/op
Iteration   3: 2.930 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.939 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.930, 2.939, 2.949), stdev = 0.010
  CI (99.9%): [2.765, 3.113] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  10.987 ms/op
                 createUser·p0.9999: 13.500 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.519 ms/op
                 createUser·p0.999:  6.538 ms/op
                 createUser·p0.9999: 12.338 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 11.078 ms/op
                 createUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387402
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 188708 
    [ 2.500,  3.750) = 194817 
    [ 3.750,  5.000) = 2933 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     12.780 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  7.142 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  6.660 ms/op
                 existUser·p0.9999: 12.975 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  6.906 ms/op
                 existUser·p0.9999: 12.434 ms/op
                 existUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392529
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 195528 
    [ 2.500,  3.750) = 193505 
    [ 3.750,  5.000) = 2577 
    [ 5.000,  6.250) = 430 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      7.077 ms/op
     p(99.9900) =     15.499 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  5.892 ms/op
                 getUser·p0.9999: 13.152 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  6.397 ms/op
                 getUser·p0.9999: 13.418 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.864 ms/op
                 getUser·p0.9999: 10.686 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388727
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 195032 
    [ 2.500,  3.750) = 188648 
    [ 3.750,  5.000) = 3712 
    [ 5.000,  6.250) = 816 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      7.400 ms/op
     p(99.9900) =     13.077 ms/op
     p(99.9990) =     14.018 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
Iteration   1: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.570 ms/op
                 listUser·p0.9999: 11.575 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.635 ms/op
                 listUser·p0.9999: 11.898 ms/op
                 listUser·p1.00:   13.681 ms/op

Iteration   3: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.297 ms/op
                 listUser·p0.9999: 11.669 ms/op
                 listUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322382
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 100116 
    [ 2.500,  3.750) = 184146 
    [ 3.750,  5.000) = 30911 
    [ 5.000,  6.250) = 5750 
    [ 6.250,  7.500) = 622 
    [ 7.500,  8.750) = 212 
    [ 8.750, 10.000) = 292 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     11.813 ms/op
     p(99.9990) =     12.661 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.917 ± 1.179  ops/ms
ClientPb.existUser                       thrpt       3  13.460 ± 1.093  ops/ms
ClientPb.getUser                         thrpt       3  12.946 ± 1.872  ops/ms
ClientPb.listUser                        thrpt       3  10.821 ± 0.656  ops/ms
ClientPb.createUser                       avgt       3   2.490 ± 0.538   ms/op
ClientPb.existUser                        avgt       3   2.402 ± 0.064   ms/op
ClientPb.getUser                          avgt       3   2.465 ± 0.272   ms/op
ClientPb.listUser                         avgt       3   2.939 ± 0.174   ms/op
ClientPb.createUser                     sample  387402   2.476 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.965           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.208           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.780           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.303           ms/op
ClientPb.existUser                      sample  392529   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.966           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.077           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.499           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.662           ms/op
ClientPb.getUser                        sample  388727   2.468 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.746           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.400           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.077           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.139           ms/op
ClientPb.listUser                       sample  322382   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.813           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.681           ms/op
