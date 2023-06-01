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
# Warmup Iteration   1: 2.574 ops/ms
# Warmup Iteration   2: 6.532 ops/ms
# Warmup Iteration   3: 9.071 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 10.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.931 ±(99.9%) 7.331 ops/ms [Average]
  (min, avg, max) = (9.534, 9.931, 10.338), stdev = 0.402
  CI (99.9%): [2.600, 17.263] (assumes normal distribution)


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
# Warmup Iteration   1: 4.081 ops/ms
# Warmup Iteration   2: 9.372 ops/ms
# Warmup Iteration   3: 9.787 ops/ms
Iteration   1: 10.438 ops/ms
Iteration   2: 10.720 ops/ms
Iteration   3: 10.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.561 ±(99.9%) 2.634 ops/ms [Average]
  (min, avg, max) = (10.438, 10.561, 10.720), stdev = 0.144
  CI (99.9%): [7.928, 13.195] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ops/ms
# Warmup Iteration   2: 9.286 ops/ms
# Warmup Iteration   3: 9.484 ops/ms
Iteration   1: 9.622 ops/ms
Iteration   2: 10.417 ops/ms
Iteration   3: 10.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.060 ±(99.9%) 7.362 ops/ms [Average]
  (min, avg, max) = (9.622, 10.060, 10.417), stdev = 0.404
  CI (99.9%): [2.698, 17.421] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.443 ops/ms
# Warmup Iteration   2: 7.831 ops/ms
# Warmup Iteration   3: 8.505 ops/ms
Iteration   1: 8.825 ops/ms
Iteration   2: 8.228 ops/ms
Iteration   3: 8.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.587 ±(99.9%) 5.773 ops/ms [Average]
  (min, avg, max) = (8.228, 8.587, 8.825), stdev = 0.316
  CI (99.9%): [2.814, 14.360] (assumes normal distribution)


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
# Warmup Iteration   1: 9.269 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.005 ms/op
Iteration   1: 3.330 ±(99.9%) 0.006 ms/op
Iteration   2: 3.236 ±(99.9%) 0.003 ms/op
Iteration   3: 3.210 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.258 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (3.210, 3.258, 3.330), stdev = 0.063
  CI (99.9%): [2.106, 4.411] (assumes normal distribution)


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
# Warmup Iteration   1: 6.846 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.004 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.053 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.058 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.034, 3.058, 3.088), stdev = 0.027
  CI (99.9%): [2.558, 3.559] (assumes normal distribution)


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
# Warmup Iteration   1: 7.714 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.003 ms/op
Iteration   1: 3.235 ±(99.9%) 0.008 ms/op
Iteration   2: 3.304 ±(99.9%) 0.007 ms/op
Iteration   3: 3.113 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.217 ±(99.9%) 1.772 ms/op [Average]
  (min, avg, max) = (3.113, 3.217, 3.304), stdev = 0.097
  CI (99.9%): [1.445, 4.990] (assumes normal distribution)


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
# Warmup Iteration   1: 10.016 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.006 ms/op
Iteration   1: 3.706 ±(99.9%) 0.009 ms/op
Iteration   2: 3.741 ±(99.9%) 0.008 ms/op
Iteration   3: 3.672 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.706 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.672, 3.706, 3.741), stdev = 0.035
  CI (99.9%): [3.072, 4.340] (assumes normal distribution)


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
# Warmup Iteration   1: 8.696 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  18.371 ms/op
                 createUser·p0.9999: 20.512 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  9.780 ms/op
                 createUser·p0.9999: 22.642 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.763 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  12.772 ms/op
                 createUser·p0.9999: 18.645 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301832
  mean =      3.179 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24524 
    [ 2.500,  5.000) = 271227 
    [ 5.000,  7.500) = 5308 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 170 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     14.863 ms/op
     p(99.9900) =     21.621 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 7.447 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  9.734 ms/op
                 existUser·p0.9999: 20.336 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   2: 3.101 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 24.795 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  13.435 ms/op
                 existUser·p0.9999: 21.010 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311109
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22842 
    [ 2.500,  5.000) = 283994 
    [ 5.000,  7.500) = 3631 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     24.379 ms/op
     p(99.9990) =     25.159 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 8.488 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.009 ms/op
Iteration   1: 3.274 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  12.374 ms/op
                 getUser·p0.9999: 20.546 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  16.974 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  13.369 ms/op
                 getUser·p0.9999: 24.549 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297337
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16373 
    [ 2.500,  5.000) = 273239 
    [ 5.000,  7.500) = 6827 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     16.149 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 10.180 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.266 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.012 ms/op
Iteration   1: 3.764 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 21.955 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   2: 3.699 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   16.040 ms/op

Iteration   3: 3.694 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 16.652 ms/op
                 listUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258250
  mean =      3.719 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 251500 
    [ 5.000,  7.500) = 4922 
    [ 7.500, 10.000) = 902 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.672 ms/op
     p(99.9900) =     21.108 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.931 ± 7.331  ops/ms
ClientPb.existUser                       thrpt       3  10.561 ± 2.634  ops/ms
ClientPb.getUser                         thrpt       3  10.060 ± 7.362  ops/ms
ClientPb.listUser                        thrpt       3   8.587 ± 5.773  ops/ms
ClientPb.createUser                       avgt       3   3.258 ± 1.153   ms/op
ClientPb.existUser                        avgt       3   3.058 ± 0.500   ms/op
ClientPb.getUser                          avgt       3   3.217 ± 1.772   ms/op
ClientPb.listUser                         avgt       3   3.706 ± 0.634   ms/op
ClientPb.createUser                     sample  301832   3.179 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.692           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.863           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.248           ms/op
ClientPb.existUser                      sample  311109   3.083 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.257           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.435           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.379           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.887           ms/op
ClientPb.getUser                        sample  297337   3.229 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.975           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.149           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.233           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.904           ms/op
ClientPb.listUser                       sample  258250   3.719 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.672           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.315           ms/op
