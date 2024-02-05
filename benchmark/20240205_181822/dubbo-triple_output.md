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
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 12.012 ops/ms
# Warmup Iteration   3: 12.441 ops/ms
Iteration   1: 12.616 ops/ms
Iteration   2: 12.703 ops/ms
Iteration   3: 12.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.672 ±(99.9%) 0.891 ops/ms [Average]
  (min, avg, max) = (12.616, 12.672, 12.703), stdev = 0.049
  CI (99.9%): [11.781, 13.563] (assumes normal distribution)


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
# Warmup Iteration   1: 7.873 ops/ms
# Warmup Iteration   2: 13.277 ops/ms
# Warmup Iteration   3: 13.286 ops/ms
Iteration   1: 13.139 ops/ms
Iteration   2: 13.397 ops/ms
Iteration   3: 13.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.275 ±(99.9%) 2.362 ops/ms [Average]
  (min, avg, max) = (13.139, 13.275, 13.397), stdev = 0.129
  CI (99.9%): [10.913, 15.637] (assumes normal distribution)


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
# Warmup Iteration   1: 8.117 ops/ms
# Warmup Iteration   2: 12.880 ops/ms
# Warmup Iteration   3: 12.916 ops/ms
Iteration   1: 12.995 ops/ms
Iteration   2: 13.209 ops/ms
Iteration   3: 12.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.068 ±(99.9%) 2.229 ops/ms [Average]
  (min, avg, max) = (12.995, 13.068, 13.209), stdev = 0.122
  CI (99.9%): [10.839, 15.297] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.779 ops/ms
# Warmup Iteration   2: 10.656 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.661 ops/ms
Iteration   2: 10.758 ops/ms
Iteration   3: 10.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.696 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (10.661, 10.696, 10.758), stdev = 0.054
  CI (99.9%): [9.709, 11.682] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.003 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.481 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.466, 2.481, 2.502), stdev = 0.019
  CI (99.9%): [2.143, 2.820] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.002 ms/op
Iteration   1: 2.424 ±(99.9%) 0.003 ms/op
Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
Iteration   3: 2.438 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.430 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.424, 2.430, 2.438), stdev = 0.007
  CI (99.9%): [2.302, 2.558] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.452, 2.461, 2.474), stdev = 0.011
  CI (99.9%): [2.255, 2.667] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.552 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
Iteration   3: 3.005 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.999 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (2.987, 2.999, 3.005), stdev = 0.011
  CI (99.9%): [2.804, 3.194] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  10.936 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  10.294 ms/op
                 createUser·p0.9999: 13.238 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   4.047 ms/op
                 createUser·p0.999:  8.121 ms/op
                 createUser·p0.9999: 9.880 ms/op
                 createUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381361
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 183655 
    [ 2.500,  3.750) = 193331 
    [ 3.750,  5.000) = 3579 
    [ 5.000,  6.250) = 321 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.153 ms/op
     p(99.9900) =     13.302 ms/op
     p(99.9990) =     14.086 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
Iteration   1: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.504 ms/op
                 existUser·p0.999:  7.764 ms/op
                 existUser·p0.9999: 14.206 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.393 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.974 ms/op
                 existUser·p0.99:   3.359 ms/op
                 existUser·p0.999:  5.633 ms/op
                 existUser·p0.9999: 12.446 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.923 ms/op
                 existUser·p0.9999: 14.280 ms/op
                 existUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397786
  mean =      2.411 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 200532 
    [ 2.500,  3.750) = 194283 
    [ 3.750,  5.000) = 2275 
    [ 5.000,  6.250) = 244 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.141 ms/op
     p(99.9900) =     13.905 ms/op
     p(99.9990) =     14.927 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.006 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.995 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  6.064 ms/op
                 getUser·p0.9999: 14.302 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.188 ms/op
                 getUser·p0.999:  7.478 ms/op
                 getUser·p0.9999: 12.749 ms/op
                 getUser·p1.00:   13.222 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  6.856 ms/op
                 getUser·p0.9999: 11.714 ms/op
                 getUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389285
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 195877 
    [ 2.500,  3.750) = 187798 
    [ 3.750,  5.000) = 4533 
    [ 5.000,  6.250) = 564 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 158 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.981 ms/op
     p(99.9000) =      6.985 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.584 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
Iteration   1: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.365 ms/op
                 listUser·p0.9999: 10.593 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 2.941 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.464 ms/op
                 listUser·p0.9999: 11.289 ms/op
                 listUser·p1.00:   13.042 ms/op

Iteration   3: 2.957 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.217 ms/op
                 listUser·p0.9999: 11.706 ms/op
                 listUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324260
  mean =      2.958 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 186 
    [ 1.250,  2.500) = 100354 
    [ 2.500,  3.750) = 188235 
    [ 3.750,  5.000) = 29017 
    [ 5.000,  6.250) = 4979 
    [ 6.250,  7.500) = 786 
    [ 7.500,  8.750) = 262 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.566 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     12.412 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.672 ± 0.891  ops/ms
ClientPb.existUser                       thrpt       3  13.275 ± 2.362  ops/ms
ClientPb.getUser                         thrpt       3  13.068 ± 2.229  ops/ms
ClientPb.listUser                        thrpt       3  10.696 ± 0.986  ops/ms
ClientPb.createUser                       avgt       3   2.481 ± 0.338   ms/op
ClientPb.existUser                        avgt       3   2.430 ± 0.128   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.206   ms/op
ClientPb.listUser                         avgt       3   2.999 ± 0.195   ms/op
ClientPb.createUser                     sample  381361   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.956           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.153           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.302           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.433           ms/op
ClientPb.existUser                      sample  397786   2.411 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.141           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.905           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  389285   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.714           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.985           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.206           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.713           ms/op
ClientPb.listUser                       sample  324260   2.958 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.791           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.566           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.042           ms/op
