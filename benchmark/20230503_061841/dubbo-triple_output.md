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
# Warmup Iteration   1: 2.475 ops/ms
# Warmup Iteration   2: 6.048 ops/ms
# Warmup Iteration   3: 9.277 ops/ms
Iteration   1: 9.521 ops/ms
Iteration   2: 10.181 ops/ms
Iteration   3: 10.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.971 ±(99.9%) 7.112 ops/ms [Average]
  (min, avg, max) = (9.521, 9.971, 10.211), stdev = 0.390
  CI (99.9%): [2.859, 17.083] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.898 ops/ms
# Warmup Iteration   2: 9.634 ops/ms
# Warmup Iteration   3: 9.816 ops/ms
Iteration   1: 10.558 ops/ms
Iteration   2: 10.882 ops/ms
Iteration   3: 10.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.514 ±(99.9%) 7.150 ops/ms [Average]
  (min, avg, max) = (10.102, 10.514, 10.882), stdev = 0.392
  CI (99.9%): [3.365, 17.664] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ops/ms
# Warmup Iteration   2: 8.960 ops/ms
# Warmup Iteration   3: 10.018 ops/ms
Iteration   1: 9.948 ops/ms
Iteration   2: 10.211 ops/ms
Iteration   3: 9.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.026 ±(99.9%) 2.943 ops/ms [Average]
  (min, avg, max) = (9.918, 10.026, 10.211), stdev = 0.161
  CI (99.9%): [7.083, 12.968] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.482 ops/ms
# Warmup Iteration   2: 7.683 ops/ms
# Warmup Iteration   3: 8.268 ops/ms
Iteration   1: 8.757 ops/ms
Iteration   2: 8.282 ops/ms
Iteration   3: 8.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.573 ±(99.9%) 4.648 ops/ms [Average]
  (min, avg, max) = (8.282, 8.573, 8.757), stdev = 0.255
  CI (99.9%): [3.925, 13.221] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.149 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.005 ms/op
Iteration   1: 3.144 ±(99.9%) 0.006 ms/op
Iteration   2: 3.218 ±(99.9%) 0.005 ms/op
Iteration   3: 3.083 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.148 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (3.083, 3.148, 3.218), stdev = 0.068
  CI (99.9%): [1.908, 4.389] (assumes normal distribution)


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
# Warmup Iteration   1: 7.752 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.002 ms/op
Iteration   1: 3.129 ±(99.9%) 0.006 ms/op
Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
Iteration   3: 3.041 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.080 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (3.041, 3.080, 3.129), stdev = 0.045
  CI (99.9%): [2.267, 3.893] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.664 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.002 ms/op
Iteration   1: 3.193 ±(99.9%) 0.004 ms/op
Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
Iteration   3: 3.213 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.183 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (3.142, 3.183, 3.213), stdev = 0.037
  CI (99.9%): [2.514, 3.852] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.020 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.005 ms/op
Iteration   1: 3.678 ±(99.9%) 0.010 ms/op
Iteration   2: 3.746 ±(99.9%) 0.008 ms/op
Iteration   3: 3.702 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.708 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (3.678, 3.708, 3.746), stdev = 0.034
  CI (99.9%): [3.081, 4.335] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.453 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
Iteration   1: 3.323 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  15.074 ms/op
                 createUser·p0.9999: 20.613 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  19.590 ms/op
                 createUser·p0.9999: 22.282 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 3.254 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  11.293 ms/op
                 createUser·p0.9999: 23.225 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296807
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19788 
    [ 2.500,  5.000) = 270721 
    [ 5.000,  7.500) = 5409 
    [ 7.500, 10.000) = 526 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     22.325 ms/op
     p(99.9990) =     24.053 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.017 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 20.808 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.612 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 21.818 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305496
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25460 
    [ 2.500,  5.000) = 274763 
    [ 5.000,  7.500) = 4662 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =      9.937 ms/op
     p(99.9900) =     21.656 ms/op
     p(99.9990) =     23.477 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.269 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.010 ms/op
Iteration   1: 3.384 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.416 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  18.063 ms/op
                 getUser·p0.9999: 30.655 ms/op
                 getUser·p1.00:   33.391 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  11.169 ms/op
                 getUser·p0.9999: 22.446 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.326 ms/op
                 getUser·p0.95:   3.482 ms/op
                 getUser·p0.99:   4.813 ms/op
                 getUser·p0.999:  9.493 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300611
  mean =      3.193 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11970 
    [ 2.500,  5.000) = 282379 
    [ 5.000,  7.500) = 5193 
    [ 7.500, 10.000) = 554 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     27.816 ms/op
     p(99.9990) =     33.190 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.283 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.012 ms/op
Iteration   1: 3.717 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 20.263 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 3.746 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 3.716 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  12.632 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257753
  mean =      3.726 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 249902 
    [ 5.000,  7.500) = 5711 
    [ 7.500, 10.000) = 1389 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     13.558 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     20.330 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.971 ± 7.112  ops/ms
ClientPb.existUser                       thrpt       3  10.514 ± 7.150  ops/ms
ClientPb.getUser                         thrpt       3  10.026 ± 2.943  ops/ms
ClientPb.listUser                        thrpt       3   8.573 ± 4.648  ops/ms
ClientPb.createUser                       avgt       3   3.148 ± 1.241   ms/op
ClientPb.existUser                        avgt       3   3.080 ± 0.813   ms/op
ClientPb.getUser                          avgt       3   3.183 ± 0.669   ms/op
ClientPb.listUser                         avgt       3   3.708 ± 0.627   ms/op
ClientPb.createUser                     sample  296807   3.232 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.908           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.325           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.216           ms/op
ClientPb.existUser                      sample  305496   3.141 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.450           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.937           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.656           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.691           ms/op
ClientPb.getUser                        sample  300611   3.193 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.416           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.576           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.581           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.816           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.391           ms/op
ClientPb.listUser                       sample  257753   3.726 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.243           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.558           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.923           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.382           ms/op
