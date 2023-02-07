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
# Warmup Iteration   1: 1.792 ops/ms
# Warmup Iteration   2: 4.234 ops/ms
# Warmup Iteration   3: 8.393 ops/ms
Iteration   1: 8.450 ops/ms
Iteration   2: 9.045 ops/ms
Iteration   3: 8.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.801 ±(99.9%) 5.690 ops/ms [Average]
  (min, avg, max) = (8.450, 8.801, 9.045), stdev = 0.312
  CI (99.9%): [3.111, 14.491] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.608 ops/ms
# Warmup Iteration   2: 7.816 ops/ms
# Warmup Iteration   3: 8.906 ops/ms
Iteration   1: 9.190 ops/ms
Iteration   2: 9.202 ops/ms
Iteration   3: 9.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.305 ±(99.9%) 3.457 ops/ms [Average]
  (min, avg, max) = (9.190, 9.305, 9.524), stdev = 0.189
  CI (99.9%): [5.848, 12.762] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.415 ops/ms
# Warmup Iteration   2: 7.422 ops/ms
# Warmup Iteration   3: 8.940 ops/ms
Iteration   1: 8.888 ops/ms
Iteration   2: 9.082 ops/ms
Iteration   3: 8.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.978 ±(99.9%) 1.783 ops/ms [Average]
  (min, avg, max) = (8.888, 8.978, 9.082), stdev = 0.098
  CI (99.9%): [7.195, 10.761] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.177 ops/ms
# Warmup Iteration   2: 6.708 ops/ms
# Warmup Iteration   3: 7.161 ops/ms
Iteration   1: 7.491 ops/ms
Iteration   2: 7.450 ops/ms
Iteration   3: 7.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.549 ±(99.9%) 2.522 ops/ms [Average]
  (min, avg, max) = (7.450, 7.549, 7.707), stdev = 0.138
  CI (99.9%): [5.027, 10.071] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.876 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.005 ms/op
Iteration   1: 3.657 ±(99.9%) 0.007 ms/op
Iteration   2: 3.557 ±(99.9%) 0.007 ms/op
Iteration   3: 3.476 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.563 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (3.476, 3.563, 3.657), stdev = 0.090
  CI (99.9%): [1.913, 5.214] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.162 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.013 ms/op
Iteration   1: 3.403 ±(99.9%) 0.009 ms/op
Iteration   2: 3.381 ±(99.9%) 0.008 ms/op
Iteration   3: 3.410 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.398 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.381, 3.398, 3.410), stdev = 0.015
  CI (99.9%): [3.123, 3.674] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.644 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.005 ms/op
Iteration   1: 3.667 ±(99.9%) 0.004 ms/op
Iteration   2: 3.719 ±(99.9%) 0.007 ms/op
Iteration   3: 3.540 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.642 ±(99.9%) 1.683 ms/op [Average]
  (min, avg, max) = (3.540, 3.642, 3.719), stdev = 0.092
  CI (99.9%): [1.959, 5.325] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.241 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.007 ms/op
Iteration   1: 4.446 ±(99.9%) 0.012 ms/op
Iteration   2: 4.304 ±(99.9%) 0.008 ms/op
Iteration   3: 4.160 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.304 ±(99.9%) 2.610 ms/op [Average]
  (min, avg, max) = (4.160, 4.304, 4.446), stdev = 0.143
  CI (99.9%): [1.693, 6.914] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.902 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.015 ms/op
Iteration   1: 3.671 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  23.852 ms/op
                 createUser·p0.9999: 26.449 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   2: 3.614 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  24.642 ms/op
                 createUser·p0.9999: 29.856 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 3.739 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  22.086 ms/op
                 createUser·p0.9999: 30.701 ms/op
                 createUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 261039
  mean =      3.674 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3424 
    [ 2.500,  5.000) = 249389 
    [ 5.000,  7.500) = 6826 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     22.968 ms/op
     p(99.9900) =     29.914 ms/op
     p(99.9990) =     32.239 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.152 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.011 ms/op
Iteration   1: 3.427 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  22.631 ms/op
                 existUser·p0.9999: 26.029 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   2: 3.567 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  10.967 ms/op
                 existUser·p0.9999: 27.007 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   3: 3.443 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  23.757 ms/op
                 existUser·p0.9999: 31.538 ms/op
                 existUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275913
  mean =      3.478 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5103 
    [ 2.500,  5.000) = 264151 
    [ 5.000,  7.500) = 5223 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     14.288 ms/op
     p(99.9900) =     29.898 ms/op
     p(99.9990) =     32.257 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.248 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.011 ms/op
Iteration   1: 3.626 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   8.124 ms/op
                 getUser·p0.999:  21.889 ms/op
                 getUser·p0.9999: 25.916 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   2: 3.649 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.788 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  25.471 ms/op
                 getUser·p0.9999: 30.835 ms/op
                 getUser·p1.00:   32.408 ms/op

Iteration   3: 3.712 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.011 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  15.126 ms/op
                 getUser·p0.9999: 31.339 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262105
  mean =      3.662 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2044 
    [ 2.500,  5.000) = 249292 
    [ 5.000,  7.500) = 8057 
    [ 7.500, 10.000) = 1944 
    [10.000, 12.500) = 405 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     18.048 ms/op
     p(99.9900) =     30.748 ms/op
     p(99.9990) =     31.941 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 15.474 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.482 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.393 ±(99.9%) 0.016 ms/op
Iteration   1: 4.288 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  25.212 ms/op
                 listUser·p0.9999: 32.246 ms/op
                 listUser·p1.00:   32.735 ms/op

Iteration   2: 4.272 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  17.631 ms/op
                 listUser·p0.9999: 25.379 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   3: 4.233 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.271 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  16.178 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225093
  mean =      4.264 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 212485 
    [ 5.000,  7.500) = 9389 
    [ 7.500, 10.000) = 2262 
    [10.000, 12.500) = 387 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.183 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     31.128 ms/op
     p(99.9990) =     32.678 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.801 ± 5.690  ops/ms
ClientPb.existUser                       thrpt       3   9.305 ± 3.457  ops/ms
ClientPb.getUser                         thrpt       3   8.978 ± 1.783  ops/ms
ClientPb.listUser                        thrpt       3   7.549 ± 2.522  ops/ms
ClientPb.createUser                       avgt       3   3.563 ± 1.651   ms/op
ClientPb.existUser                        avgt       3   3.398 ± 0.276   ms/op
ClientPb.getUser                          avgt       3   3.642 ± 1.683   ms/op
ClientPb.listUser                         avgt       3   4.304 ± 2.610   ms/op
ClientPb.createUser                     sample  261039   3.674 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.395           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.968           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.914           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.539           ms/op
ClientPb.existUser                      sample  275913   3.478 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.376           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.288           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.898           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.834           ms/op
ClientPb.getUser                        sample  262105   3.662 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.702           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.048           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.748           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.408           ms/op
ClientPb.listUser                       sample  225093   4.264 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.183           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.596           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.128           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.735           ms/op
