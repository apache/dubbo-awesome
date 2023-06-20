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
# Warmup Iteration   1: 2.347 ops/ms
# Warmup Iteration   2: 6.209 ops/ms
# Warmup Iteration   3: 9.003 ops/ms
Iteration   1: 9.416 ops/ms
Iteration   2: 9.557 ops/ms
Iteration   3: 9.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.435 ±(99.9%) 2.095 ops/ms [Average]
  (min, avg, max) = (9.330, 9.435, 9.557), stdev = 0.115
  CI (99.9%): [7.340, 11.529] (assumes normal distribution)


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
# Warmup Iteration   1: 2.920 ops/ms
# Warmup Iteration   2: 8.705 ops/ms
# Warmup Iteration   3: 9.602 ops/ms
Iteration   1: 9.969 ops/ms
Iteration   2: 9.904 ops/ms
Iteration   3: 9.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.868 ±(99.9%) 2.242 ops/ms [Average]
  (min, avg, max) = (9.731, 9.868, 9.969), stdev = 0.123
  CI (99.9%): [7.626, 12.110] (assumes normal distribution)


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
# Warmup Iteration   1: 3.164 ops/ms
# Warmup Iteration   2: 8.495 ops/ms
# Warmup Iteration   3: 9.043 ops/ms
Iteration   1: 9.609 ops/ms
Iteration   2: 9.629 ops/ms
Iteration   3: 9.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.456 ±(99.9%) 5.164 ops/ms [Average]
  (min, avg, max) = (9.129, 9.456, 9.629), stdev = 0.283
  CI (99.9%): [4.292, 14.620] (assumes normal distribution)


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
# Warmup Iteration   1: 2.834 ops/ms
# Warmup Iteration   2: 7.248 ops/ms
# Warmup Iteration   3: 8.236 ops/ms
Iteration   1: 8.158 ops/ms
Iteration   2: 7.875 ops/ms
Iteration   3: 8.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.041 ±(99.9%) 2.697 ops/ms [Average]
  (min, avg, max) = (7.875, 8.041, 8.158), stdev = 0.148
  CI (99.9%): [5.344, 10.737] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.186 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.006 ms/op
Iteration   1: 3.356 ±(99.9%) 0.007 ms/op
Iteration   2: 3.376 ±(99.9%) 0.011 ms/op
Iteration   3: 3.330 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.354 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (3.330, 3.354, 3.376), stdev = 0.023
  CI (99.9%): [2.939, 3.769] (assumes normal distribution)


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
# Warmup Iteration   1: 9.267 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.009 ms/op
Iteration   1: 3.181 ±(99.9%) 0.010 ms/op
Iteration   2: 3.253 ±(99.9%) 0.007 ms/op
Iteration   3: 3.237 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.223 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (3.181, 3.223, 3.253), stdev = 0.038
  CI (99.9%): [2.532, 3.915] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.833 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.006 ms/op
Iteration   1: 3.443 ±(99.9%) 0.009 ms/op
Iteration   2: 3.446 ±(99.9%) 0.009 ms/op
Iteration   3: 3.336 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.408 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.336, 3.408, 3.446), stdev = 0.062
  CI (99.9%): [2.273, 4.543] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.326 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.011 ms/op
Iteration   1: 3.872 ±(99.9%) 0.012 ms/op
Iteration   2: 3.871 ±(99.9%) 0.008 ms/op
Iteration   3: 3.879 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.874 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (3.871, 3.874, 3.879), stdev = 0.004
  CI (99.9%): [3.793, 3.955] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.544 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.009 ms/op
Iteration   1: 3.392 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  19.763 ms/op
                 createUser·p0.9999: 27.558 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  19.394 ms/op
                 createUser·p0.9999: 24.510 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  17.578 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284353
  mean =      3.374 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13114 
    [ 2.500,  5.000) = 264333 
    [ 5.000,  7.500) = 6091 
    [ 7.500, 10.000) = 359 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     17.704 ms/op
     p(99.9900) =     26.350 ms/op
     p(99.9990) =     28.275 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 7.234 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.008 ms/op
Iteration   1: 3.315 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.612 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  17.052 ms/op
                 existUser·p0.9999: 23.791 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.710 ms/op
                 existUser·p0.999:  9.555 ms/op
                 existUser·p0.9999: 24.478 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   3: 3.319 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.322 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  8.339 ms/op
                 existUser·p0.9999: 31.928 ms/op
                 existUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293167
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18794 
    [ 2.500,  5.000) = 269666 
    [ 5.000,  7.500) = 3929 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.322 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     13.268 ms/op
     p(99.9900) =     30.005 ms/op
     p(99.9990) =     32.215 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 9.820 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.011 ms/op
Iteration   1: 3.367 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  19.919 ms/op
                 getUser·p0.9999: 22.446 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 3.352 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  21.054 ms/op
                 getUser·p0.9999: 32.226 ms/op
                 getUser·p1.00:   33.948 ms/op

Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  23.254 ms/op
                 getUser·p0.9999: 26.444 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285313
  mean =      3.366 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13578 
    [ 2.500,  5.000) = 265313 
    [ 5.000,  7.500) = 5555 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     20.044 ms/op
     p(99.9900) =     31.374 ms/op
     p(99.9990) =     33.564 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 10.460 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.016 ms/op
Iteration   1: 4.019 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  16.922 ms/op
                 listUser·p0.9999: 24.512 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 3.881 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.526 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.945 ms/op
                 listUser·p0.999:  15.754 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.914 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  14.112 ms/op
                 listUser·p0.9999: 17.394 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243633
  mean =      3.937 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 236611 
    [ 5.000,  7.500) = 4653 
    [ 7.500, 10.000) = 1495 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     25.023 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.435 ± 2.095  ops/ms
ClientPb.existUser                       thrpt       3   9.868 ± 2.242  ops/ms
ClientPb.getUser                         thrpt       3   9.456 ± 5.164  ops/ms
ClientPb.listUser                        thrpt       3   8.041 ± 2.697  ops/ms
ClientPb.createUser                       avgt       3   3.354 ± 0.415   ms/op
ClientPb.existUser                        avgt       3   3.223 ± 0.692   ms/op
ClientPb.getUser                          avgt       3   3.408 ± 1.135   ms/op
ClientPb.listUser                         avgt       3   3.874 ± 0.081   ms/op
ClientPb.createUser                     sample  284353   3.374 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.704           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.350           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  293167   3.274 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.322           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.268           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.005           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.342           ms/op
ClientPb.getUser                        sample  285313   3.366 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.208           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.044           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.374           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.948           ms/op
ClientPb.listUser                       sample  243633   3.937 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.526           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.429           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.264           ms/op
