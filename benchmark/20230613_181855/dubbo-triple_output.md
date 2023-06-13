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
# Warmup Iteration   1: 2.514 ops/ms
# Warmup Iteration   2: 5.904 ops/ms
# Warmup Iteration   3: 9.228 ops/ms
Iteration   1: 9.617 ops/ms
Iteration   2: 10.000 ops/ms
Iteration   3: 9.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.786 ±(99.9%) 3.568 ops/ms [Average]
  (min, avg, max) = (9.617, 9.786, 10.000), stdev = 0.196
  CI (99.9%): [6.219, 13.354] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.435 ops/ms
# Warmup Iteration   2: 8.855 ops/ms
# Warmup Iteration   3: 9.857 ops/ms
Iteration   1: 10.041 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.334 ±(99.9%) 4.724 ops/ms [Average]
  (min, avg, max) = (10.041, 10.334, 10.530), stdev = 0.259
  CI (99.9%): [5.610, 15.059] (assumes normal distribution)


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
# Warmup Iteration   1: 3.496 ops/ms
# Warmup Iteration   2: 8.940 ops/ms
# Warmup Iteration   3: 9.308 ops/ms
Iteration   1: 10.009 ops/ms
Iteration   2: 9.716 ops/ms
Iteration   3: 9.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.833 ±(99.9%) 2.824 ops/ms [Average]
  (min, avg, max) = (9.716, 9.833, 10.009), stdev = 0.155
  CI (99.9%): [7.009, 12.657] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.284 ops/ms
# Warmup Iteration   2: 7.188 ops/ms
# Warmup Iteration   3: 8.504 ops/ms
Iteration   1: 8.418 ops/ms
Iteration   2: 8.540 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.444 ±(99.9%) 1.567 ops/ms [Average]
  (min, avg, max) = (8.374, 8.444, 8.540), stdev = 0.086
  CI (99.9%): [6.876, 10.011] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.611 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
Iteration   1: 3.242 ±(99.9%) 0.004 ms/op
Iteration   2: 3.271 ±(99.9%) 0.003 ms/op
Iteration   3: 3.142 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.218 ±(99.9%) 1.233 ms/op [Average]
  (min, avg, max) = (3.142, 3.218, 3.271), stdev = 0.068
  CI (99.9%): [1.985, 4.451] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.721 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.004 ms/op
Iteration   1: 3.217 ±(99.9%) 0.008 ms/op
Iteration   2: 3.118 ±(99.9%) 0.003 ms/op
Iteration   3: 3.045 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.127 ±(99.9%) 1.571 ms/op [Average]
  (min, avg, max) = (3.045, 3.127, 3.217), stdev = 0.086
  CI (99.9%): [1.556, 4.697] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.744 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.005 ms/op
Iteration   1: 3.242 ±(99.9%) 0.007 ms/op
Iteration   2: 3.284 ±(99.9%) 0.006 ms/op
Iteration   3: 3.318 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.281 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.242, 3.281, 3.318), stdev = 0.038
  CI (99.9%): [2.587, 3.976] (assumes normal distribution)


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
# Warmup Iteration   1: 9.478 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.006 ms/op
Iteration   1: 3.910 ±(99.9%) 0.008 ms/op
Iteration   2: 3.730 ±(99.9%) 0.009 ms/op
Iteration   3: 3.819 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.820 ±(99.9%) 1.646 ms/op [Average]
  (min, avg, max) = (3.730, 3.820, 3.910), stdev = 0.090
  CI (99.9%): [2.174, 5.465] (assumes normal distribution)


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
# Warmup Iteration   1: 8.317 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.009 ms/op
Iteration   1: 3.362 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  18.035 ms/op
                 createUser·p0.9999: 20.889 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 23.855 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.188 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   5.059 ms/op
                 createUser·p0.999:  10.595 ms/op
                 createUser·p0.9999: 20.904 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294617
  mean =      3.255 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23337 
    [ 2.500,  5.000) = 265990 
    [ 5.000,  7.500) = 4631 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     16.000 ms/op
     p(99.9900) =     23.202 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.205 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.008 ms/op
Iteration   1: 3.158 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  7.987 ms/op
                 existUser·p0.9999: 19.553 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.142 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 21.322 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 21.538 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305285
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32154 
    [ 2.500,  5.000) = 269525 
    [ 5.000,  7.500) = 3059 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =      9.205 ms/op
     p(99.9900) =     21.315 ms/op
     p(99.9990) =     22.437 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 8.664 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.010 ms/op
Iteration   1: 3.286 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  17.725 ms/op
                 getUser·p0.9999: 20.450 ms/op
                 getUser·p1.00:   21.496 ms/op

Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 22.221 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  13.337 ms/op
                 getUser·p0.9999: 25.936 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295071
  mean =      3.253 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11940 
    [ 2.500,  5.000) = 276129 
    [ 5.000,  7.500) = 5980 
    [ 7.500, 10.000) = 477 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     16.611 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 8.498 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.012 ms/op
Iteration   1: 3.815 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 20.299 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 3.772 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.643 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 3.800 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 16.966 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252642
  mean =      3.796 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 246220 
    [ 5.000,  7.500) = 4278 
    [ 7.500, 10.000) = 1415 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     20.528 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.786 ± 3.568  ops/ms
ClientPb.existUser                       thrpt       3  10.334 ± 4.724  ops/ms
ClientPb.getUser                         thrpt       3   9.833 ± 2.824  ops/ms
ClientPb.listUser                        thrpt       3   8.444 ± 1.567  ops/ms
ClientPb.createUser                       avgt       3   3.218 ± 1.233   ms/op
ClientPb.existUser                        avgt       3   3.127 ± 1.571   ms/op
ClientPb.getUser                          avgt       3   3.281 ± 0.694   ms/op
ClientPb.listUser                         avgt       3   3.820 ± 1.646   ms/op
ClientPb.createUser                     sample  294617   3.255 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.777           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.000           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.202           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.576           ms/op
ClientPb.existUser                      sample  305285   3.145 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.106           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.177           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.205           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.315           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.069           ms/op
ClientPb.getUser                        sample  295071   3.253 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.178           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.611           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.740           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.296           ms/op
ClientPb.listUser                       sample  252642   3.796 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.202           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.516           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.528           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.610           ms/op
