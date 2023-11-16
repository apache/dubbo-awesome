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
# Warmup Iteration   1: 4.748 ops/ms
# Warmup Iteration   2: 12.119 ops/ms
# Warmup Iteration   3: 12.314 ops/ms
Iteration   1: 12.293 ops/ms
Iteration   2: 12.564 ops/ms
Iteration   3: 12.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.519 ±(99.9%) 3.766 ops/ms [Average]
  (min, avg, max) = (12.293, 12.519, 12.699), stdev = 0.206
  CI (99.9%): [8.753, 16.284] (assumes normal distribution)


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
# Warmup Iteration   1: 8.132 ops/ms
# Warmup Iteration   2: 12.786 ops/ms
# Warmup Iteration   3: 12.799 ops/ms
Iteration   1: 12.911 ops/ms
Iteration   2: 12.860 ops/ms
Iteration   3: 12.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.828 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (12.714, 12.828, 12.911), stdev = 0.102
  CI (99.9%): [10.963, 14.693] (assumes normal distribution)


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
# Warmup Iteration   1: 7.843 ops/ms
# Warmup Iteration   2: 12.569 ops/ms
# Warmup Iteration   3: 12.569 ops/ms
Iteration   1: 12.639 ops/ms
Iteration   2: 12.709 ops/ms
Iteration   3: 12.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.633 ±(99.9%) 1.454 ops/ms [Average]
  (min, avg, max) = (12.550, 12.633, 12.709), stdev = 0.080
  CI (99.9%): [11.179, 14.086] (assumes normal distribution)


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
# Warmup Iteration   1: 6.365 ops/ms
# Warmup Iteration   2: 10.391 ops/ms
# Warmup Iteration   3: 10.452 ops/ms
Iteration   1: 10.497 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.514 ±(99.9%) 0.611 ops/ms [Average]
  (min, avg, max) = (10.492, 10.514, 10.552), stdev = 0.033
  CI (99.9%): [9.903, 11.124] (assumes normal distribution)


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.686 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.004 ms/op
Iteration   1: 2.609 ±(99.9%) 0.004 ms/op
Iteration   2: 2.613 ±(99.9%) 0.004 ms/op
Iteration   3: 2.597 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.606 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (2.597, 2.606, 2.613), stdev = 0.008
  CI (99.9%): [2.453, 2.760] (assumes normal distribution)


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.529 ±(99.9%) 0.023 ms/op [Average]
  (min, avg, max) = (2.527, 2.529, 2.530), stdev = 0.001
  CI (99.9%): [2.506, 2.552] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.005 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.545 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.526, 2.545, 2.562), stdev = 0.018
  CI (99.9%): [2.210, 2.879] (assumes normal distribution)


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.006 ms/op
Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
Iteration   3: 3.040 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.014, 3.034, 3.049), stdev = 0.018
  CI (99.9%): [2.707, 3.362] (assumes normal distribution)


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.705 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.602 ±(99.9%) 0.006 ms/op
Iteration   1: 2.632 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   4.997 ms/op
                 createUser·p0.999:  12.370 ms/op
                 createUser·p0.9999: 14.090 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.591 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.742 ms/op
                 createUser·p0.9999: 12.544 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   3: 2.606 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.623 ms/op
                 createUser·p0.9999: 12.808 ms/op
                 createUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 367491
  mean =      2.609 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 172832 
    [ 2.500,  3.750) = 187138 
    [ 3.750,  5.000) = 5554 
    [ 5.000,  6.250) = 1420 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.162 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.799 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.390 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  10.173 ms/op
                 existUser·p0.9999: 14.341 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  6.737 ms/op
                 existUser·p0.9999: 12.963 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  8.376 ms/op
                 existUser·p0.9999: 12.412 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383785
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 186791 
    [ 2.500,  3.750) = 192479 
    [ 3.750,  5.000) = 3518 
    [ 5.000,  6.250) = 471 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.843 ms/op
     p(99.9000) =      7.258 ms/op
     p(99.9900) =     13.869 ms/op
     p(99.9990) =     15.111 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  12.533 ms/op
                 getUser·p0.9999: 14.762 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 16.237 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  9.519 ms/op
                 getUser·p0.9999: 11.731 ms/op
                 getUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376532
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 181941 
    [ 2.500,  3.750) = 188148 
    [ 3.750,  5.000) = 4856 
    [ 5.000,  6.250) = 1025 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     16.974 ms/op
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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.009 ms/op
Iteration   1: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 11.941 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   2: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 10.840 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   3: 3.091 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.479 ms/op
                 listUser·p0.9999: 11.408 ms/op
                 listUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311231
  mean =      3.082 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 79337 
    [ 2.500,  3.750) = 188612 
    [ 3.750,  5.000) = 35226 
    [ 5.000,  6.250) = 6476 
    [ 6.250,  7.500) = 762 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 296 
    [10.000, 11.250) = 174 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.597 ms/op
     p(99.9900) =     11.352 ms/op
     p(99.9990) =     12.572 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.519 ± 3.766  ops/ms
ClientPb.existUser                       thrpt       3  12.828 ± 1.865  ops/ms
ClientPb.getUser                         thrpt       3  12.633 ± 1.454  ops/ms
ClientPb.listUser                        thrpt       3  10.514 ± 0.611  ops/ms
ClientPb.createUser                       avgt       3   2.606 ± 0.153   ms/op
ClientPb.existUser                        avgt       3   2.529 ± 0.023   ms/op
ClientPb.getUser                          avgt       3   2.545 ± 0.335   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.328   ms/op
ClientPb.createUser                     sample  367491   2.609 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.761           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.666           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.799           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.615           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.516           ms/op
ClientPb.existUser                      sample  383785   2.499 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.743           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.843           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.258           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.869           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.270           ms/op
ClientPb.getUser                        sample  376532   2.547 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.465           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.404           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.942           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.138           ms/op
ClientPb.listUser                       sample  311231   3.082 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.597           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.352           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.698           ms/op
