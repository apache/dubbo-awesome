# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.113 ops/ms
# Warmup Iteration   2: 5.497 ops/ms
# Warmup Iteration   3: 8.652 ops/ms
Iteration   1: 9.441 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.351 ±(99.9%) 4.657 ops/ms [Average]
  (min, avg, max) = (9.063, 9.351, 9.549), stdev = 0.255
  CI (99.9%): [4.694, 14.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.225 ops/ms
# Warmup Iteration   2: 8.746 ops/ms
# Warmup Iteration   3: 9.304 ops/ms
Iteration   1: 9.836 ops/ms
Iteration   2: 9.687 ops/ms
Iteration   3: 9.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.833 ±(99.9%) 2.617 ops/ms [Average]
  (min, avg, max) = (9.687, 9.833, 9.974), stdev = 0.143
  CI (99.9%): [7.216, 12.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.955 ops/ms
# Warmup Iteration   2: 8.649 ops/ms
# Warmup Iteration   3: 9.460 ops/ms
Iteration   1: 9.216 ops/ms
Iteration   2: 9.557 ops/ms
Iteration   3: 9.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.353 ±(99.9%) 3.293 ops/ms [Average]
  (min, avg, max) = (9.216, 9.353, 9.557), stdev = 0.181
  CI (99.9%): [6.060, 12.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.905 ops/ms
# Warmup Iteration   2: 7.280 ops/ms
# Warmup Iteration   3: 7.832 ops/ms
Iteration   1: 8.111 ops/ms
Iteration   2: 8.187 ops/ms
Iteration   3: 8.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.153 ±(99.9%) 0.708 ops/ms [Average]
  (min, avg, max) = (8.111, 8.153, 8.187), stdev = 0.039
  CI (99.9%): [7.445, 8.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.727 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.006 ms/op
Iteration   1: 3.456 ±(99.9%) 0.006 ms/op
Iteration   2: 3.237 ±(99.9%) 0.013 ms/op
Iteration   3: 3.390 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.361 ±(99.9%) 2.054 ms/op [Average]
  (min, avg, max) = (3.237, 3.361, 3.456), stdev = 0.113
  CI (99.9%): [1.307, 5.415] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.809 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.006 ms/op
Iteration   1: 3.216 ±(99.9%) 0.009 ms/op
Iteration   2: 3.253 ±(99.9%) 0.005 ms/op
Iteration   3: 3.224 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.231 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (3.216, 3.231, 3.253), stdev = 0.019
  CI (99.9%): [2.876, 3.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.355 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.004 ms/op
Iteration   1: 3.450 ±(99.9%) 0.010 ms/op
Iteration   2: 3.322 ±(99.9%) 0.009 ms/op
Iteration   3: 3.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.427 ±(99.9%) 1.749 ms/op [Average]
  (min, avg, max) = (3.322, 3.427, 3.510), stdev = 0.096
  CI (99.9%): [1.678, 5.176] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.776 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.004 ms/op
Iteration   1: 3.936 ±(99.9%) 0.007 ms/op
Iteration   2: 3.923 ±(99.9%) 0.011 ms/op
Iteration   3: 3.972 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.944 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.923, 3.944, 3.972), stdev = 0.025
  CI (99.9%): [3.489, 4.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.753 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.011 ms/op
Iteration   1: 3.365 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  20.020 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   2: 3.284 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  11.354 ms/op
                 createUser·p0.9999: 37.360 ms/op
                 createUser·p1.00:   38.207 ms/op

Iteration   3: 3.325 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  23.942 ms/op
                 createUser·p0.9999: 27.694 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288504
  mean =      3.324 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10331 
    [ 2.500,  5.000) = 273165 
    [ 5.000,  7.500) = 3988 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     19.840 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     37.822 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.807 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.010 ms/op
Iteration   1: 3.290 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  10.054 ms/op
                 existUser·p0.9999: 29.158 ms/op
                 existUser·p1.00:   29.655 ms/op

Iteration   2: 3.420 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  21.958 ms/op
                 existUser·p0.9999: 26.507 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 3.351 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  20.040 ms/op
                 existUser·p0.9999: 26.539 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286198
  mean =      3.353 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5466 
    [ 2.500,  5.000) = 274344 
    [ 5.000,  7.500) = 5477 
    [ 7.500, 10.000) = 395 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     20.198 ms/op
     p(99.9900) =     27.701 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.429 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
Iteration   1: 3.539 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 23.652 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   2: 3.379 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  22.422 ms/op
                 getUser·p0.9999: 26.937 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 3.390 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  20.601 ms/op
                 getUser·p0.9999: 26.069 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279466
  mean =      3.434 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2438 
    [ 2.500,  5.000) = 271006 
    [ 5.000,  7.500) = 5116 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     13.453 ms/op
     p(99.9900) =     26.152 ms/op
     p(99.9990) =     27.219 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.368 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.013 ms/op
Iteration   1: 3.990 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.625 ms/op
                 listUser·p0.999:  16.675 ms/op
                 listUser·p0.9999: 29.424 ms/op
                 listUser·p1.00:   30.736 ms/op

Iteration   2: 3.902 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.405 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  14.303 ms/op
                 listUser·p0.9999: 16.577 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  16.473 ms/op
                 listUser·p0.9999: 21.046 ms/op
                 listUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240635
  mean =      3.985 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 230874 
    [ 5.000,  7.500) = 7359 
    [ 7.500, 10.000) = 1407 
    [10.000, 12.500) = 409 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     28.273 ms/op
     p(99.9990) =     30.276 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.351 ± 4.657  ops/ms
ClientPb.existUser                       thrpt       3   9.833 ± 2.617  ops/ms
ClientPb.getUser                         thrpt       3   9.353 ± 3.293  ops/ms
ClientPb.listUser                        thrpt       3   8.153 ± 0.708  ops/ms
ClientPb.createUser                       avgt       3   3.361 ± 2.054   ms/op
ClientPb.existUser                        avgt       3   3.231 ± 0.356   ms/op
ClientPb.getUser                          avgt       3   3.427 ± 1.749   ms/op
ClientPb.listUser                         avgt       3   3.944 ± 0.455   ms/op
ClientPb.createUser                     sample  288504   3.324 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.360           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.840           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.882           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.207           ms/op
ClientPb.existUser                      sample  286198   3.353 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.198           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.701           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.655           ms/op
ClientPb.getUser                        sample  279466   3.434 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.126           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.453           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.152           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.591           ms/op
ClientPb.listUser                       sample  240635   3.985 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.270           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.273           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.736           ms/op
