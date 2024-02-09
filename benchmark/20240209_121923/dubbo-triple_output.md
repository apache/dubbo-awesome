# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.539 ops/ms
# Warmup Iteration   2: 11.820 ops/ms
# Warmup Iteration   3: 12.060 ops/ms
Iteration   1: 12.369 ops/ms
Iteration   2: 12.326 ops/ms
Iteration   3: 12.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.371 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (12.326, 12.371, 12.418), stdev = 0.046
  CI (99.9%): [11.529, 13.212] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.151 ops/ms
# Warmup Iteration   2: 12.870 ops/ms
# Warmup Iteration   3: 12.955 ops/ms
Iteration   1: 13.081 ops/ms
Iteration   2: 13.131 ops/ms
Iteration   3: 13.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.095 ±(99.9%) 0.585 ops/ms [Average]
  (min, avg, max) = (13.072, 13.095, 13.131), stdev = 0.032
  CI (99.9%): [12.509, 13.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.513 ops/ms
# Warmup Iteration   2: 12.429 ops/ms
# Warmup Iteration   3: 12.684 ops/ms
Iteration   1: 12.251 ops/ms
Iteration   2: 12.531 ops/ms
Iteration   3: 12.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.448 ±(99.9%) 3.128 ops/ms [Average]
  (min, avg, max) = (12.251, 12.448, 12.562), stdev = 0.171
  CI (99.9%): [9.320, 15.576] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.415 ops/ms
# Warmup Iteration   2: 10.245 ops/ms
# Warmup Iteration   3: 10.412 ops/ms
Iteration   1: 10.507 ops/ms
Iteration   2: 10.696 ops/ms
Iteration   3: 10.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.585 ±(99.9%) 1.804 ops/ms [Average]
  (min, avg, max) = (10.507, 10.585, 10.696), stdev = 0.099
  CI (99.9%): [8.780, 12.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.584 ±(99.9%) 0.004 ms/op
Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
Iteration   3: 2.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.569 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.554, 2.569, 2.584), stdev = 0.015
  CI (99.9%): [2.296, 2.841] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.626 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.003 ms/op
Iteration   3: 2.447 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.447, 2.457, 2.463), stdev = 0.009
  CI (99.9%): [2.298, 2.616] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.003 ms/op
Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
Iteration   3: 2.545 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.520 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (2.501, 2.520, 2.545), stdev = 0.023
  CI (99.9%): [2.105, 2.934] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.786 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.005 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.013 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (3.008, 3.013, 3.022), stdev = 0.008
  CI (99.9%): [2.875, 3.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.437 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 2.706 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  11.805 ms/op
                 createUser·p0.9999: 14.172 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  9.661 ms/op
                 createUser·p0.9999: 12.068 ms/op
                 createUser·p1.00:   12.386 ms/op

Iteration   3: 2.601 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   4.051 ms/op
                 createUser·p0.999:  8.455 ms/op
                 createUser·p0.9999: 10.437 ms/op
                 createUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373739
  mean =      2.566 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 177275 
    [ 2.500,  3.750) = 191919 
    [ 3.750,  5.000) = 3568 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.279 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.857 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  12.278 ms/op
                 existUser·p0.9999: 14.671 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  6.184 ms/op
                 existUser·p0.9999: 14.110 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 11.604 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382971
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 188312 
    [ 2.500,  3.750) = 190778 
    [ 3.750,  5.000) = 3042 
    [ 5.000,  6.250) = 404 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      6.333 ms/op
     p(99.9900) =     14.123 ms/op
     p(99.9990) =     15.158 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.035 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.654 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.557 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.025 ms/op
                 getUser·p0.999:  11.844 ms/op
                 getUser·p0.9999: 14.459 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 2.572 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  9.800 ms/op
                 getUser·p0.9999: 13.905 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.794 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 12.075 ms/op
                 getUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374985
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 182099 
    [ 2.500,  3.750) = 187681 
    [ 3.750,  5.000) = 4402 
    [ 5.000,  6.250) = 374 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     13.918 ms/op
     p(99.9990) =     15.012 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.865 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.009 ms/op
Iteration   1: 3.096 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.519 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 11.507 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   3: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.259 ms/op
                 listUser·p0.9999: 11.266 ms/op
                 listUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310564
  mean =      3.088 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 80097 
    [ 2.500,  3.750) = 186128 
    [ 3.750,  5.000) = 36026 
    [ 5.000,  6.250) = 6725 
    [ 6.250,  7.500) = 836 
    [ 7.500,  8.750) = 212 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.452 ms/op
     p(99.9990) =     11.877 ms/op
     p(99.9999) =     11.944 ms/op
    p(100.0000) =     11.944 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.371 ± 0.842  ops/ms
ClientPb.existUser                       thrpt       3  13.095 ± 0.585  ops/ms
ClientPb.getUser                         thrpt       3  12.448 ± 3.128  ops/ms
ClientPb.listUser                        thrpt       3  10.585 ± 1.804  ops/ms
ClientPb.createUser                       avgt       3   2.569 ± 0.272   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.159   ms/op
ClientPb.getUser                          avgt       3   2.520 ± 0.415   ms/op
ClientPb.listUser                         avgt       3   3.013 ± 0.138   ms/op
ClientPb.createUser                     sample  373739   2.566 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.938           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.471           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.581           ms/op
ClientPb.existUser                      sample  382971   2.504 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.877           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.333           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.123           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.434           ms/op
ClientPb.getUser                        sample  374985   2.558 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.922           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.880           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.918           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.172           ms/op
ClientPb.listUser                       sample  310564   3.088 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.452           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.944           ms/op
