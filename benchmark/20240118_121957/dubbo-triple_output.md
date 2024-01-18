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
# Warmup Iteration   1: 4.892 ops/ms
# Warmup Iteration   2: 11.900 ops/ms
# Warmup Iteration   3: 12.424 ops/ms
Iteration   1: 12.564 ops/ms
Iteration   2: 12.508 ops/ms
Iteration   3: 12.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.540 ±(99.9%) 0.532 ops/ms [Average]
  (min, avg, max) = (12.508, 12.540, 12.564), stdev = 0.029
  CI (99.9%): [12.008, 13.073] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.900 ops/ms
# Warmup Iteration   2: 12.890 ops/ms
# Warmup Iteration   3: 12.897 ops/ms
Iteration   1: 12.992 ops/ms
Iteration   2: 13.005 ops/ms
Iteration   3: 12.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.963 ±(99.9%) 1.127 ops/ms [Average]
  (min, avg, max) = (12.892, 12.963, 13.005), stdev = 0.062
  CI (99.9%): [11.835, 14.090] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.749 ops/ms
# Warmup Iteration   2: 12.406 ops/ms
# Warmup Iteration   3: 12.601 ops/ms
Iteration   1: 12.784 ops/ms
Iteration   2: 12.608 ops/ms
Iteration   3: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.630 ±(99.9%) 2.638 ops/ms [Average]
  (min, avg, max) = (12.497, 12.630, 12.784), stdev = 0.145
  CI (99.9%): [9.992, 15.268] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.710 ops/ms
# Warmup Iteration   2: 10.508 ops/ms
# Warmup Iteration   3: 10.587 ops/ms
Iteration   1: 10.618 ops/ms
Iteration   2: 10.533 ops/ms
Iteration   3: 10.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.586 ±(99.9%) 0.839 ops/ms [Average]
  (min, avg, max) = (10.533, 10.586, 10.618), stdev = 0.046
  CI (99.9%): [9.747, 11.425] (assumes normal distribution)


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.615 ±(99.9%) 0.005 ms/op
Iteration   1: 2.618 ±(99.9%) 0.004 ms/op
Iteration   2: 2.595 ±(99.9%) 0.004 ms/op
Iteration   3: 2.572 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.595 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (2.572, 2.595, 2.618), stdev = 0.023
  CI (99.9%): [2.175, 3.015] (assumes normal distribution)


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.003 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.468, 2.477, 2.486), stdev = 0.009
  CI (99.9%): [2.315, 2.639] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.003 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.504 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.497, 2.504, 2.507), stdev = 0.005
  CI (99.9%): [2.404, 2.603] (assumes normal distribution)


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
# Warmup Iteration   1: 4.532 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
Iteration   2: 2.971 ±(99.9%) 0.005 ms/op
Iteration   3: 2.943 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.958 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.943, 2.958, 2.971), stdev = 0.014
  CI (99.9%): [2.707, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.712 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.550 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.717 ms/op
                 createUser·p0.999:  11.234 ms/op
                 createUser·p0.9999: 14.252 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.248 ms/op
                 createUser·p0.9999: 12.435 ms/op
                 createUser·p1.00:   13.222 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 11.217 ms/op
                 createUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375580
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 180210 
    [ 2.500,  3.750) = 191379 
    [ 3.750,  5.000) = 3052 
    [ 5.000,  6.250) = 465 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      9.149 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.717 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.400 ms/op
                 existUser·p0.999:  5.812 ms/op
                 existUser·p0.9999: 13.662 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  5.497 ms/op
                 existUser·p0.9999: 12.714 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.964 ms/op
                 existUser·p0.9999: 12.993 ms/op
                 existUser·p1.00:   14.631 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394490
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 196336 
    [ 2.500,  3.750) = 195836 
    [ 3.750,  5.000) = 1639 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 151 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      5.722 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.506 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  11.187 ms/op
                 getUser·p0.9999: 13.772 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.864 ms/op
                 getUser·p0.9999: 12.680 ms/op
                 getUser·p1.00:   13.042 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  5.380 ms/op
                 getUser·p0.9999: 10.898 ms/op
                 getUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382755
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 187596 
    [ 2.500,  3.750) = 189619 
    [ 3.750,  5.000) = 4390 
    [ 5.000,  6.250) = 659 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =      7.244 ms/op
     p(99.9900) =     13.348 ms/op
     p(99.9990) =     14.230 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 4.890 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.969 ms/op
                 listUser·p0.9999: 10.522 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   2: 2.942 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 11.133 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   3: 2.945 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   5.262 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324840
  mean =      2.953 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 102358 
    [ 2.500,  3.750) = 187755 
    [ 3.750,  5.000) = 28611 
    [ 5.000,  6.250) = 4776 
    [ 6.250,  7.500) = 515 
    [ 7.500,  8.750) = 260 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     10.961 ms/op
     p(99.9990) =     11.801 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.540 ± 0.532  ops/ms
ClientPb.existUser                       thrpt       3  12.963 ± 1.127  ops/ms
ClientPb.getUser                         thrpt       3  12.630 ± 2.638  ops/ms
ClientPb.listUser                        thrpt       3  10.586 ± 0.839  ops/ms
ClientPb.createUser                       avgt       3   2.595 ± 0.420   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.162   ms/op
ClientPb.getUser                          avgt       3   2.504 ± 0.099   ms/op
ClientPb.listUser                         avgt       3   2.958 ± 0.251   ms/op
ClientPb.createUser                     sample  375580   2.553 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.946           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.149           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.353           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.762           ms/op
ClientPb.existUser                      sample  394490   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.821           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.722           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.664           ms/op
ClientPb.getUser                        sample  382755   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.827           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.244           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.348           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.287           ms/op
ClientPb.listUser                       sample  324840   2.953 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.869           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.961           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.075           ms/op
