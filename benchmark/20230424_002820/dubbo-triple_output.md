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
# Warmup Iteration   1: 2.307 ops/ms
# Warmup Iteration   2: 6.023 ops/ms
# Warmup Iteration   3: 8.428 ops/ms
Iteration   1: 9.121 ops/ms
Iteration   2: 9.281 ops/ms
Iteration   3: 9.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.228 ±(99.9%) 1.690 ops/ms [Average]
  (min, avg, max) = (9.121, 9.228, 9.283), stdev = 0.093
  CI (99.9%): [7.539, 10.918] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.295 ops/ms
# Warmup Iteration   2: 8.878 ops/ms
# Warmup Iteration   3: 9.540 ops/ms
Iteration   1: 9.217 ops/ms
Iteration   2: 9.328 ops/ms
Iteration   3: 9.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.459 ±(99.9%) 5.989 ops/ms [Average]
  (min, avg, max) = (9.217, 9.459, 9.833), stdev = 0.328
  CI (99.9%): [3.470, 15.448] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.153 ops/ms
# Warmup Iteration   2: 7.852 ops/ms
# Warmup Iteration   3: 9.225 ops/ms
Iteration   1: 9.377 ops/ms
Iteration   2: 9.394 ops/ms
Iteration   3: 9.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.413 ±(99.9%) 0.889 ops/ms [Average]
  (min, avg, max) = (9.377, 9.413, 9.468), stdev = 0.049
  CI (99.9%): [8.524, 10.302] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.781 ops/ms
# Warmup Iteration   2: 7.375 ops/ms
# Warmup Iteration   3: 7.712 ops/ms
Iteration   1: 8.045 ops/ms
Iteration   2: 8.055 ops/ms
Iteration   3: 8.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.079 ±(99.9%) 0.909 ops/ms [Average]
  (min, avg, max) = (8.045, 8.079, 8.136), stdev = 0.050
  CI (99.9%): [7.170, 8.987] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.746 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.007 ms/op
Iteration   1: 3.494 ±(99.9%) 0.007 ms/op
Iteration   2: 3.451 ±(99.9%) 0.005 ms/op
Iteration   3: 3.361 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.435 ±(99.9%) 1.235 ms/op [Average]
  (min, avg, max) = (3.361, 3.435, 3.494), stdev = 0.068
  CI (99.9%): [2.200, 4.670] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.145 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.008 ms/op
Iteration   1: 3.201 ±(99.9%) 0.009 ms/op
Iteration   2: 3.253 ±(99.9%) 0.010 ms/op
Iteration   3: 3.246 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.233 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (3.201, 3.233, 3.253), stdev = 0.028
  CI (99.9%): [2.716, 3.750] (assumes normal distribution)


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
# Warmup Iteration   1: 8.361 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.005 ms/op
Iteration   1: 3.468 ±(99.9%) 0.009 ms/op
Iteration   2: 3.418 ±(99.9%) 0.003 ms/op
Iteration   3: 3.448 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.445 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.418, 3.445, 3.468), stdev = 0.025
  CI (99.9%): [2.985, 3.905] (assumes normal distribution)


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
# Warmup Iteration   1: 10.310 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.502 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.008 ms/op
Iteration   1: 4.168 ±(99.9%) 0.006 ms/op
Iteration   2: 4.096 ±(99.9%) 0.008 ms/op
Iteration   3: 4.002 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.088 ±(99.9%) 1.516 ms/op [Average]
  (min, avg, max) = (4.002, 4.088, 4.168), stdev = 0.083
  CI (99.9%): [2.573, 5.604] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.160 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.009 ms/op
Iteration   1: 3.438 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.045 ms/op
                 createUser·p0.999:  17.786 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.319 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.852 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  17.865 ms/op
                 createUser·p0.9999: 22.917 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 3.604 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  16.426 ms/op
                 createUser·p0.9999: 24.942 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278142
  mean =      3.450 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8001 
    [ 2.500,  5.000) = 261596 
    [ 5.000,  7.500) = 7285 
    [ 7.500, 10.000) = 711 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     16.609 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 8.340 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.008 ms/op
Iteration   1: 3.446 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  19.846 ms/op
                 existUser·p0.9999: 33.545 ms/op
                 existUser·p1.00:   34.931 ms/op

Iteration   2: 3.435 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  21.853 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 3.384 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  17.105 ms/op
                 existUser·p0.9999: 26.858 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280371
  mean =      3.422 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12228 
    [ 2.500,  5.000) = 260529 
    [ 5.000,  7.500) = 6418 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     17.650 ms/op
     p(99.9900) =     32.079 ms/op
     p(99.9990) =     34.236 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 9.423 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.012 ms/op
Iteration   1: 3.487 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  17.532 ms/op
                 getUser·p0.9999: 25.974 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 3.463 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  19.213 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 3.404 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  12.594 ms/op
                 getUser·p0.9999: 29.157 ms/op
                 getUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278002
  mean =      3.451 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5494 
    [ 2.500,  5.000) = 265519 
    [ 5.000,  7.500) = 5782 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     28.384 ms/op
     p(99.9990) =     30.252 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 10.565 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.461 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.013 ms/op
Iteration   1: 3.990 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 22.771 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 3.942 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.720 ms/op
                 listUser·p0.9999: 23.233 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 3.981 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 23.331 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241588
  mean =      3.971 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 234674 
    [ 5.000,  7.500) = 4885 
    [ 7.500, 10.000) = 1218 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.038 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.228 ± 1.690  ops/ms
ClientPb.existUser                       thrpt       3   9.459 ± 5.989  ops/ms
ClientPb.getUser                         thrpt       3   9.413 ± 0.889  ops/ms
ClientPb.listUser                        thrpt       3   8.079 ± 0.909  ops/ms
ClientPb.createUser                       avgt       3   3.435 ± 1.235   ms/op
ClientPb.existUser                        avgt       3   3.233 ± 0.517   ms/op
ClientPb.getUser                          avgt       3   3.445 ± 0.460   ms/op
ClientPb.listUser                         avgt       3   4.088 ± 1.516   ms/op
ClientPb.createUser                     sample  278142   3.450 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.776           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.609           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.462           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.542           ms/op
ClientPb.existUser                      sample  280371   3.422 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.498           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.650           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  278002   3.451 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.237           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.960           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.384           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.376           ms/op
ClientPb.listUser                       sample  241588   3.971 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.724           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.385           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.233           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.412           ms/op
