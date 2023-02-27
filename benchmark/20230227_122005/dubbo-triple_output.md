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
# Warmup Iteration   1: 2.546 ops/ms
# Warmup Iteration   2: 6.075 ops/ms
# Warmup Iteration   3: 9.168 ops/ms
Iteration   1: 9.762 ops/ms
Iteration   2: 9.859 ops/ms
Iteration   3: 10.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.881 ±(99.9%) 2.384 ops/ms [Average]
  (min, avg, max) = (9.762, 9.881, 10.021), stdev = 0.131
  CI (99.9%): [7.497, 12.265] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ops/ms
# Warmup Iteration   2: 9.785 ops/ms
# Warmup Iteration   3: 10.027 ops/ms
Iteration   1: 10.719 ops/ms
Iteration   2: 10.706 ops/ms
Iteration   3: 10.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.538 ±(99.9%) 5.514 ops/ms [Average]
  (min, avg, max) = (10.189, 10.538, 10.719), stdev = 0.302
  CI (99.9%): [5.024, 16.052] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 9.026 ops/ms
# Warmup Iteration   3: 9.540 ops/ms
Iteration   1: 9.707 ops/ms
Iteration   2: 9.727 ops/ms
Iteration   3: 9.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.670 ±(99.9%) 1.478 ops/ms [Average]
  (min, avg, max) = (9.577, 9.670, 9.727), stdev = 0.081
  CI (99.9%): [8.192, 11.148] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 7.456 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 8.776 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.562 ±(99.9%) 4.311 ops/ms [Average]
  (min, avg, max) = (8.308, 8.562, 8.776), stdev = 0.236
  CI (99.9%): [4.251, 12.873] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.694 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.001 ms/op
Iteration   1: 3.148 ±(99.9%) 0.005 ms/op
Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
Iteration   3: 3.257 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.201 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (3.148, 3.201, 3.257), stdev = 0.054
  CI (99.9%): [2.210, 4.193] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.383 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.004 ms/op
Iteration   1: 3.054 ±(99.9%) 0.005 ms/op
Iteration   2: 3.118 ±(99.9%) 0.004 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.061 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (3.012, 3.061, 3.118), stdev = 0.053
  CI (99.9%): [2.086, 4.037] (assumes normal distribution)


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
# Warmup Iteration   1: 7.963 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.004 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
Iteration   3: 3.192 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.215 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (3.192, 3.215, 3.234), stdev = 0.022
  CI (99.9%): [2.819, 3.610] (assumes normal distribution)


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
# Warmup Iteration   1: 9.377 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.005 ms/op
Iteration   1: 3.771 ±(99.9%) 0.011 ms/op
Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
Iteration   3: 3.687 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.734 ±(99.9%) 0.780 ms/op [Average]
  (min, avg, max) = (3.687, 3.734, 3.771), stdev = 0.043
  CI (99.9%): [2.954, 4.514] (assumes normal distribution)


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
# Warmup Iteration   1: 7.422 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.163 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  19.723 ms/op
                 createUser·p0.9999: 23.557 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  9.982 ms/op
                 createUser·p0.9999: 23.157 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.296 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.324 ms/op
                 createUser·p0.999:  14.549 ms/op
                 createUser·p0.9999: 22.053 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301018
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17693 
    [ 2.500,  5.000) = 278169 
    [ 5.000,  7.500) = 4458 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.422 ms/op
     p(99.9000) =     18.218 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 7.218 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
Iteration   1: 3.131 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  10.022 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  8.274 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   3: 3.151 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  16.728 ms/op
                 existUser·p0.9999: 33.620 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303621
  mean =      3.160 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23474 
    [ 2.500,  5.000) = 274107 
    [ 5.000,  7.500) = 5223 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     33.051 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 8.131 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
Iteration   1: 3.344 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  18.723 ms/op
                 getUser·p0.9999: 23.804 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  9.503 ms/op
                 getUser·p0.9999: 22.838 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   3: 3.229 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  10.518 ms/op
                 getUser·p0.9999: 21.037 ms/op
                 getUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294803
  mean =      3.254 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16001 
    [ 2.500,  5.000) = 271314 
    [ 5.000,  7.500) = 6474 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     22.742 ms/op
     p(99.9990) =     24.873 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 8.863 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.011 ms/op
Iteration   1: 3.745 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.319 ms/op
                 listUser·p0.9999: 17.085 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 3.628 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   3.961 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  12.321 ms/op
                 listUser·p0.9999: 13.648 ms/op
                 listUser·p1.00:   14.205 ms/op

Iteration   3: 3.830 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  13.787 ms/op
                 listUser·p0.9999: 16.204 ms/op
                 listUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256983
  mean =      3.732 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 42 
    [ 2.500,  3.750) = 192941 
    [ 3.750,  5.000) = 57049 
    [ 5.000,  6.250) = 2742 
    [ 6.250,  7.500) = 2539 
    [ 7.500,  8.750) = 730 
    [ 8.750, 10.000) = 271 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 249 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 87 
    [15.000, 16.250) = 72 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     16.204 ms/op
     p(99.9990) =     17.644 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.881 ± 2.384  ops/ms
ClientPb.existUser                       thrpt       3  10.538 ± 5.514  ops/ms
ClientPb.getUser                         thrpt       3   9.670 ± 1.478  ops/ms
ClientPb.listUser                        thrpt       3   8.562 ± 4.311  ops/ms
ClientPb.createUser                       avgt       3   3.201 ± 0.991   ms/op
ClientPb.existUser                        avgt       3   3.061 ± 0.975   ms/op
ClientPb.getUser                          avgt       3   3.215 ± 0.395   ms/op
ClientPb.listUser                         avgt       3   3.734 ± 0.780   ms/op
ClientPb.createUser                     sample  301018   3.186 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.178           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.422           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.218           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.200           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.052           ms/op
ClientPb.existUser                      sample  303621   3.160 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.077           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.222           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.051           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  294803   3.254 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.276           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.828           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.742           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.002           ms/op
ClientPb.listUser                       sample  256983   3.732 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.097           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.717           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.681           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.204           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.957           ms/op
