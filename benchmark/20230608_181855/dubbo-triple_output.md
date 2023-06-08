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
# Warmup Iteration   1: 1.688 ops/ms
# Warmup Iteration   2: 5.305 ops/ms
# Warmup Iteration   3: 8.454 ops/ms
Iteration   1: 9.114 ops/ms
Iteration   2: 9.207 ops/ms
Iteration   3: 9.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.192 ±(99.9%) 1.308 ops/ms [Average]
  (min, avg, max) = (9.114, 9.192, 9.255), stdev = 0.072
  CI (99.9%): [7.885, 10.500] (assumes normal distribution)


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
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 8.198 ops/ms
# Warmup Iteration   3: 9.185 ops/ms
Iteration   1: 9.652 ops/ms
Iteration   2: 9.578 ops/ms
Iteration   3: 9.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.624 ±(99.9%) 0.736 ops/ms [Average]
  (min, avg, max) = (9.578, 9.624, 9.652), stdev = 0.040
  CI (99.9%): [8.888, 10.361] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.982 ops/ms
# Warmup Iteration   2: 8.187 ops/ms
# Warmup Iteration   3: 8.993 ops/ms
Iteration   1: 8.590 ops/ms
Iteration   2: 9.448 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.136 ±(99.9%) 8.660 ops/ms [Average]
  (min, avg, max) = (8.590, 9.136, 9.448), stdev = 0.475
  CI (99.9%): [0.476, 17.796] (assumes normal distribution)


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
# Warmup Iteration   1: 2.657 ops/ms
# Warmup Iteration   2: 7.197 ops/ms
# Warmup Iteration   3: 7.760 ops/ms
Iteration   1: 7.657 ops/ms
Iteration   2: 7.840 ops/ms
Iteration   3: 8.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.863 ±(99.9%) 3.985 ops/ms [Average]
  (min, avg, max) = (7.657, 7.863, 8.092), stdev = 0.218
  CI (99.9%): [3.878, 11.849] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.328 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.567 ±(99.9%) 0.010 ms/op
Iteration   1: 3.483 ±(99.9%) 0.005 ms/op
Iteration   2: 3.512 ±(99.9%) 0.007 ms/op
Iteration   3: 3.473 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.489 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.473, 3.489, 3.512), stdev = 0.021
  CI (99.9%): [3.113, 3.866] (assumes normal distribution)


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
# Warmup Iteration   1: 7.885 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.005 ms/op
Iteration   1: 3.220 ±(99.9%) 0.005 ms/op
Iteration   2: 3.446 ±(99.9%) 0.008 ms/op
Iteration   3: 3.338 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.335 ±(99.9%) 2.061 ms/op [Average]
  (min, avg, max) = (3.220, 3.335, 3.446), stdev = 0.113
  CI (99.9%): [1.273, 5.396] (assumes normal distribution)


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
# Warmup Iteration   1: 9.586 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.006 ms/op
Iteration   1: 3.433 ±(99.9%) 0.004 ms/op
Iteration   2: 3.366 ±(99.9%) 0.006 ms/op
Iteration   3: 3.429 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.409 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.366, 3.409, 3.433), stdev = 0.038
  CI (99.9%): [2.720, 4.098] (assumes normal distribution)


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
# Warmup Iteration   1: 11.737 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.008 ms/op
Iteration   1: 4.073 ±(99.9%) 0.009 ms/op
Iteration   2: 3.989 ±(99.9%) 0.013 ms/op
Iteration   3: 4.064 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.042 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (3.989, 4.042, 4.073), stdev = 0.046
  CI (99.9%): [3.198, 4.886] (assumes normal distribution)


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
# Warmup Iteration   1: 11.494 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.014 ms/op
Iteration   1: 3.655 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   7.307 ms/op
                 createUser·p0.999:  22.412 ms/op
                 createUser·p0.9999: 25.632 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   2: 3.527 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  23.468 ms/op
                 createUser·p0.9999: 27.359 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  20.873 ms/op
                 createUser·p0.9999: 30.138 ms/op
                 createUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271128
  mean =      3.543 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5719 
    [ 2.500,  5.000) = 255798 
    [ 5.000,  7.500) = 7922 
    [ 7.500, 10.000) = 1003 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     21.791 ms/op
     p(99.9900) =     28.537 ms/op
     p(99.9990) =     31.116 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 9.529 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.010 ms/op
Iteration   1: 3.318 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 34.626 ms/op
                 existUser·p1.00:   35.521 ms/op

Iteration   2: 3.340 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  26.092 ms/op
                 existUser·p0.9999: 33.423 ms/op
                 existUser·p1.00:   34.800 ms/op

Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.298 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.196 ms/op
                 existUser·p0.999:  10.519 ms/op
                 existUser·p0.9999: 29.609 ms/op
                 existUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289298
  mean =      3.317 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5954 
    [ 2.500,  5.000) = 278635 
    [ 5.000,  7.500) = 3881 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     11.361 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.671 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.010 ms/op
Iteration   1: 3.617 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   7.422 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 23.664 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 3.423 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.800 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  20.994 ms/op
                 getUser·p0.9999: 24.312 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.466 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.741 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.855 ms/op
                 getUser·p0.999:  20.437 ms/op
                 getUser·p0.9999: 30.008 ms/op
                 getUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274250
  mean =      3.500 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7008 
    [ 2.500,  5.000) = 256537 
    [ 5.000,  7.500) = 8834 
    [ 7.500, 10.000) = 1241 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     28.068 ms/op
     p(99.9990) =     30.344 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.491 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.014 ms/op
Iteration   1: 4.086 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  21.122 ms/op
                 listUser·p0.9999: 25.202 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   2: 3.951 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.839 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.118 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.925 ms/op
                 listUser·p0.999:  15.991 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 4.003 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.939 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.317 ms/op
                 listUser·p0.999:  17.834 ms/op
                 listUser·p0.9999: 23.627 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239247
  mean =      4.013 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 230303 
    [ 5.000,  7.500) = 6730 
    [ 7.500, 10.000) = 1353 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     23.792 ms/op
     p(99.9990) =     25.751 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.192 ± 1.308  ops/ms
ClientPb.existUser                       thrpt       3   9.624 ± 0.736  ops/ms
ClientPb.getUser                         thrpt       3   9.136 ± 8.660  ops/ms
ClientPb.listUser                        thrpt       3   7.863 ± 3.985  ops/ms
ClientPb.createUser                       avgt       3   3.489 ± 0.376   ms/op
ClientPb.existUser                        avgt       3   3.335 ± 2.061   ms/op
ClientPb.getUser                          avgt       3   3.409 ± 0.689   ms/op
ClientPb.listUser                         avgt       3   4.042 ± 0.844   ms/op
ClientPb.createUser                     sample  271128   3.543 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.532           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.676           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.791           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.537           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.162           ms/op
ClientPb.existUser                      sample  289298   3.317 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.059           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.361           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.948           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.521           ms/op
ClientPb.getUser                        sample  274250   3.500 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.368           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.792           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.068           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.671           ms/op
ClientPb.listUser                       sample  239247   4.013 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.839           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.760           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.792           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.739           ms/op
