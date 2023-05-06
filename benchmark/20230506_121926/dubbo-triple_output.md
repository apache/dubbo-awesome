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
# Warmup Iteration   1: 2.338 ops/ms
# Warmup Iteration   2: 5.658 ops/ms
# Warmup Iteration   3: 9.072 ops/ms
Iteration   1: 9.673 ops/ms
Iteration   2: 9.791 ops/ms
Iteration   3: 9.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.639 ±(99.9%) 3.107 ops/ms [Average]
  (min, avg, max) = (9.455, 9.639, 9.791), stdev = 0.170
  CI (99.9%): [6.532, 12.747] (assumes normal distribution)


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
# Warmup Iteration   1: 3.204 ops/ms
# Warmup Iteration   2: 9.131 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 10.431 ops/ms
Iteration   2: 10.302 ops/ms
Iteration   3: 9.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.235 ±(99.9%) 4.321 ops/ms [Average]
  (min, avg, max) = (9.972, 10.235, 10.431), stdev = 0.237
  CI (99.9%): [5.915, 14.556] (assumes normal distribution)


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
# Warmup Iteration   1: 3.322 ops/ms
# Warmup Iteration   2: 9.203 ops/ms
# Warmup Iteration   3: 9.261 ops/ms
Iteration   1: 9.780 ops/ms
Iteration   2: 9.356 ops/ms
Iteration   3: 9.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.582 ±(99.9%) 3.896 ops/ms [Average]
  (min, avg, max) = (9.356, 9.582, 9.780), stdev = 0.214
  CI (99.9%): [5.687, 13.478] (assumes normal distribution)


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
# Warmup Iteration   1: 3.233 ops/ms
# Warmup Iteration   2: 6.545 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 8.298 ops/ms
Iteration   2: 8.359 ops/ms
Iteration   3: 8.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.366 ±(99.9%) 1.309 ops/ms [Average]
  (min, avg, max) = (8.298, 8.366, 8.441), stdev = 0.072
  CI (99.9%): [7.057, 9.674] (assumes normal distribution)


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
# Warmup Iteration   1: 9.189 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.012 ms/op
Iteration   1: 3.362 ±(99.9%) 0.004 ms/op
Iteration   2: 3.131 ±(99.9%) 0.005 ms/op
Iteration   3: 3.189 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.227 ±(99.9%) 2.198 ms/op [Average]
  (min, avg, max) = (3.131, 3.227, 3.362), stdev = 0.120
  CI (99.9%): [1.030, 5.425] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.806 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.002 ms/op
Iteration   1: 3.082 ±(99.9%) 0.003 ms/op
Iteration   2: 3.118 ±(99.9%) 0.004 ms/op
Iteration   3: 3.133 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.111 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.082, 3.111, 3.133), stdev = 0.026
  CI (99.9%): [2.630, 3.591] (assumes normal distribution)


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
# Warmup Iteration   1: 9.228 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.005 ms/op
Iteration   1: 3.163 ±(99.9%) 0.005 ms/op
Iteration   2: 3.195 ±(99.9%) 0.005 ms/op
Iteration   3: 3.185 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.181 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (3.163, 3.181, 3.195), stdev = 0.016
  CI (99.9%): [2.883, 3.479] (assumes normal distribution)


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
# Warmup Iteration   1: 9.474 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.009 ms/op
Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
Iteration   2: 3.754 ±(99.9%) 0.011 ms/op
Iteration   3: 3.908 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.821 ±(99.9%) 1.437 ms/op [Average]
  (min, avg, max) = (3.754, 3.821, 3.908), stdev = 0.079
  CI (99.9%): [2.384, 5.257] (assumes normal distribution)


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
# Warmup Iteration   1: 9.475 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.009 ms/op
Iteration   1: 3.312 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  13.903 ms/op
                 createUser·p0.9999: 19.967 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  18.623 ms/op
                 createUser·p0.9999: 22.360 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   3: 3.404 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  13.816 ms/op
                 createUser·p0.9999: 22.378 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286664
  mean =      3.346 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20385 
    [ 2.500,  5.000) = 259700 
    [ 5.000,  7.500) = 5785 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.348 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 8.326 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.008 ms/op
Iteration   1: 3.085 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  10.532 ms/op
                 existUser·p0.9999: 23.218 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   2: 3.178 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   6.051 ms/op
                 existUser·p0.999:  14.090 ms/op
                 existUser·p0.9999: 24.110 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   3: 3.134 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.880 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306071
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19076 
    [ 2.500,  5.000) = 281462 
    [ 5.000,  7.500) = 4501 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     13.466 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     24.410 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 7.891 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.361 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  19.361 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 3.239 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  19.896 ms/op
                 getUser·p0.9999: 27.672 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 3.280 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.808 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  9.247 ms/op
                 getUser·p0.9999: 19.210 ms/op
                 getUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291547
  mean =      3.293 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19688 
    [ 2.500,  5.000) = 264057 
    [ 5.000,  7.500) = 6596 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     26.766 ms/op
     p(99.9990) =     28.773 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 9.517 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.013 ms/op
Iteration   1: 3.829 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  14.655 ms/op
                 listUser·p0.9999: 20.567 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 3.871 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 15.662 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.817 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.324 ms/op
                 listUser·p0.9999: 15.110 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250009
  mean =      3.839 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 241423 
    [ 5.000,  7.500) = 6084 
    [ 7.500, 10.000) = 1721 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.639 ± 3.107  ops/ms
ClientPb.existUser                       thrpt       3  10.235 ± 4.321  ops/ms
ClientPb.getUser                         thrpt       3   9.582 ± 3.896  ops/ms
ClientPb.listUser                        thrpt       3   8.366 ± 1.309  ops/ms
ClientPb.createUser                       avgt       3   3.227 ± 2.198   ms/op
ClientPb.existUser                        avgt       3   3.111 ± 0.481   ms/op
ClientPb.getUser                          avgt       3   3.181 ± 0.298   ms/op
ClientPb.listUser                         avgt       3   3.821 ± 1.437   ms/op
ClientPb.createUser                     sample  286664   3.346 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.044           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.812           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.086           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.347           ms/op
ClientPb.existUser                      sample  306071   3.132 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.157           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.466           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.036           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.656           ms/op
ClientPb.getUser                        sample  291547   3.293 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.255           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.186           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.766           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.196           ms/op
ClientPb.listUser                       sample  250009   3.839 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.152           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.986           ms/op
