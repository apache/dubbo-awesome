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
# Warmup Iteration   1: 2.301 ops/ms
# Warmup Iteration   2: 5.966 ops/ms
# Warmup Iteration   3: 9.130 ops/ms
Iteration   1: 9.775 ops/ms
Iteration   2: 10.190 ops/ms
Iteration   3: 9.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.889 ±(99.9%) 4.800 ops/ms [Average]
  (min, avg, max) = (9.703, 9.889, 10.190), stdev = 0.263
  CI (99.9%): [5.089, 14.690] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.670 ops/ms
# Warmup Iteration   2: 9.217 ops/ms
# Warmup Iteration   3: 10.116 ops/ms
Iteration   1: 10.271 ops/ms
Iteration   2: 9.977 ops/ms
Iteration   3: 10.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.202 ±(99.9%) 3.638 ops/ms [Average]
  (min, avg, max) = (9.977, 10.202, 10.358), stdev = 0.199
  CI (99.9%): [6.564, 13.840] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.165 ops/ms
# Warmup Iteration   2: 7.573 ops/ms
# Warmup Iteration   3: 9.325 ops/ms
Iteration   1: 9.702 ops/ms
Iteration   2: 10.257 ops/ms
Iteration   3: 9.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.979 ±(99.9%) 5.071 ops/ms [Average]
  (min, avg, max) = (9.702, 9.979, 10.257), stdev = 0.278
  CI (99.9%): [4.908, 15.050] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.544 ops/ms
# Warmup Iteration   2: 7.927 ops/ms
# Warmup Iteration   3: 8.235 ops/ms
Iteration   1: 8.503 ops/ms
Iteration   2: 8.596 ops/ms
Iteration   3: 8.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.567 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (8.503, 8.567, 8.602), stdev = 0.056
  CI (99.9%): [7.546, 9.588] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.344 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.010 ms/op
Iteration   1: 3.431 ±(99.9%) 0.004 ms/op
Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
Iteration   3: 3.189 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.270 ±(99.9%) 2.542 ms/op [Average]
  (min, avg, max) = (3.189, 3.270, 3.431), stdev = 0.139
  CI (99.9%): [0.728, 5.812] (assumes normal distribution)


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
# Warmup Iteration   1: 8.234 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.006 ms/op
Iteration   1: 3.178 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.139 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.114 ±(99.9%) 1.447 ms/op [Average]
  (min, avg, max) = (3.026, 3.114, 3.178), stdev = 0.079
  CI (99.9%): [1.668, 4.561] (assumes normal distribution)


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
# Warmup Iteration   1: 7.510 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.005 ms/op
Iteration   1: 3.265 ±(99.9%) 0.007 ms/op
Iteration   2: 3.268 ±(99.9%) 0.006 ms/op
Iteration   3: 3.275 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.269 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (3.265, 3.269, 3.275), stdev = 0.005
  CI (99.9%): [3.175, 3.363] (assumes normal distribution)


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
# Warmup Iteration   1: 9.165 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.007 ms/op
Iteration   1: 3.711 ±(99.9%) 0.012 ms/op
Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
Iteration   3: 3.799 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.772 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.711, 3.772, 3.805), stdev = 0.052
  CI (99.9%): [2.817, 4.726] (assumes normal distribution)


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
# Warmup Iteration   1: 8.444 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  13.707 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  11.325 ms/op
                 createUser·p0.9999: 26.249 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.308 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  17.210 ms/op
                 createUser·p0.9999: 23.615 ms/op
                 createUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296228
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9515 
    [ 2.500,  5.000) = 281460 
    [ 5.000,  7.500) = 4222 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     16.741 ms/op
     p(99.9900) =     25.244 ms/op
     p(99.9990) =     26.715 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 7.713 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
Iteration   1: 3.266 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.877 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  13.942 ms/op
                 existUser·p0.9999: 20.755 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  9.471 ms/op
                 existUser·p0.9999: 22.839 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 27.841 ms/op
                 existUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301516
  mean =      3.183 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21981 
    [ 2.500,  5.000) = 274299 
    [ 5.000,  7.500) = 4409 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     11.944 ms/op
     p(99.9900) =     26.227 ms/op
     p(99.9990) =     28.766 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 9.189 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
Iteration   1: 3.254 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  19.071 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  8.990 ms/op
                 getUser·p0.9999: 23.859 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   5.028 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 24.378 ms/op
                 getUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297523
  mean =      3.224 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6315 
    [ 2.500,  5.000) = 284670 
    [ 5.000,  7.500) = 5750 
    [ 7.500, 10.000) = 408 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     17.186 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     24.977 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 10.708 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.012 ms/op
Iteration   1: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.468 ms/op
                 listUser·p0.9999: 21.971 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 3.797 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.697 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   3.895 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255870
  mean =      3.752 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 248804 
    [ 5.000,  7.500) = 5260 
    [ 7.500, 10.000) = 1124 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.879 ms/op
     p(99.9900) =     20.954 ms/op
     p(99.9990) =     22.770 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.889 ± 4.800  ops/ms
ClientPb.existUser                       thrpt       3  10.202 ± 3.638  ops/ms
ClientPb.getUser                         thrpt       3   9.979 ± 5.071  ops/ms
ClientPb.listUser                        thrpt       3   8.567 ± 1.021  ops/ms
ClientPb.createUser                       avgt       3   3.270 ± 2.542   ms/op
ClientPb.existUser                        avgt       3   3.114 ± 1.447   ms/op
ClientPb.getUser                          avgt       3   3.269 ± 0.094   ms/op
ClientPb.listUser                         avgt       3   3.772 ± 0.954   ms/op
ClientPb.createUser                     sample  296228   3.238 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.741           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.244           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  301516   3.183 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.636           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.944           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.227           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.869           ms/op
ClientPb.getUser                        sample  297523   3.224 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.114           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.547           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.186           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.593           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.395           ms/op
ClientPb.listUser                       sample  255870   3.752 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.217           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.879           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.954           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.807           ms/op
