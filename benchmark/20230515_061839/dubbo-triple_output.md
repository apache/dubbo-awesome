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
# Warmup Iteration   1: 2.250 ops/ms
# Warmup Iteration   2: 5.412 ops/ms
# Warmup Iteration   3: 9.077 ops/ms
Iteration   1: 9.544 ops/ms
Iteration   2: 9.139 ops/ms
Iteration   3: 9.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.342 ±(99.9%) 3.695 ops/ms [Average]
  (min, avg, max) = (9.139, 9.342, 9.544), stdev = 0.203
  CI (99.9%): [5.647, 13.038] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.197 ops/ms
# Warmup Iteration   2: 9.275 ops/ms
# Warmup Iteration   3: 9.468 ops/ms
Iteration   1: 9.878 ops/ms
Iteration   2: 9.864 ops/ms
Iteration   3: 10.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.926 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (9.864, 9.926, 10.037), stdev = 0.096
  CI (99.9%): [8.173, 11.679] (assumes normal distribution)


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
# Warmup Iteration   1: 3.224 ops/ms
# Warmup Iteration   2: 8.731 ops/ms
# Warmup Iteration   3: 9.085 ops/ms
Iteration   1: 9.579 ops/ms
Iteration   2: 9.201 ops/ms
Iteration   3: 9.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.421 ±(99.9%) 3.582 ops/ms [Average]
  (min, avg, max) = (9.201, 9.421, 9.579), stdev = 0.196
  CI (99.9%): [5.839, 13.003] (assumes normal distribution)


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
# Warmup Iteration   1: 3.102 ops/ms
# Warmup Iteration   2: 7.541 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 7.934 ops/ms
Iteration   2: 8.002 ops/ms
Iteration   3: 8.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.068 ±(99.9%) 3.214 ops/ms [Average]
  (min, avg, max) = (7.934, 8.068, 8.268), stdev = 0.176
  CI (99.9%): [4.854, 11.282] (assumes normal distribution)


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
# Warmup Iteration   1: 8.088 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.004 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
Iteration   2: 3.319 ±(99.9%) 0.006 ms/op
Iteration   3: 3.256 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.295 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.256, 3.295, 3.319), stdev = 0.034
  CI (99.9%): [2.673, 3.916] (assumes normal distribution)


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
# Warmup Iteration   1: 9.619 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.006 ms/op
Iteration   1: 3.178 ±(99.9%) 0.003 ms/op
Iteration   2: 3.318 ±(99.9%) 0.009 ms/op
Iteration   3: 3.263 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.253 ±(99.9%) 1.286 ms/op [Average]
  (min, avg, max) = (3.178, 3.253, 3.318), stdev = 0.070
  CI (99.9%): [1.967, 4.539] (assumes normal distribution)


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
# Warmup Iteration   1: 9.081 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.006 ms/op
Iteration   1: 3.431 ±(99.9%) 0.006 ms/op
Iteration   2: 3.375 ±(99.9%) 0.007 ms/op
Iteration   3: 3.334 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.380 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.334, 3.380, 3.431), stdev = 0.049
  CI (99.9%): [2.491, 4.269] (assumes normal distribution)


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
# Warmup Iteration   1: 9.337 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.014 ms/op
Iteration   1: 4.184 ±(99.9%) 0.011 ms/op
Iteration   2: 3.997 ±(99.9%) 0.010 ms/op
Iteration   3: 3.927 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.036 ±(99.9%) 2.419 ms/op [Average]
  (min, avg, max) = (3.927, 4.036, 4.184), stdev = 0.133
  CI (99.9%): [1.617, 6.455] (assumes normal distribution)


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
# Warmup Iteration   1: 9.048 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
Iteration   1: 3.456 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 22.568 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 3.376 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.634 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  20.843 ms/op
                 createUser·p0.9999: 23.872 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 3.376 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.359 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 24.691 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282193
  mean =      3.402 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12872 
    [ 2.500,  5.000) = 262313 
    [ 5.000,  7.500) = 6081 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     24.912 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 7.162 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.008 ms/op
Iteration   1: 3.306 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.955 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 22.378 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  11.030 ms/op
                 existUser·p0.9999: 24.849 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  13.226 ms/op
                 existUser·p0.9999: 25.428 ms/op
                 existUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293379
  mean =      3.271 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5240 
    [ 2.500,  5.000) = 283187 
    [ 5.000,  7.500) = 3908 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     12.249 ms/op
     p(99.9900) =     24.827 ms/op
     p(99.9990) =     26.099 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 8.604 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.011 ms/op
Iteration   1: 3.498 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  19.755 ms/op
                 getUser·p0.9999: 23.261 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.321 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.473 ms/op
                 getUser·p0.999:  20.150 ms/op
                 getUser·p0.9999: 26.837 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  18.901 ms/op
                 getUser·p0.9999: 25.359 ms/op
                 getUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283202
  mean =      3.386 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 880 
    [ 2.500,  5.000) = 274886 
    [ 5.000,  7.500) = 6090 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     25.811 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 10.981 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.012 ms/op
Iteration   1: 3.987 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.026 ms/op
                 listUser·p0.999:  20.502 ms/op
                 listUser·p0.9999: 25.819 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   2: 3.939 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 22.508 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 4.045 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.519 ms/op
                 listUser·p0.999:  14.269 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240656
  mean =      3.990 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 230974 
    [ 5.000,  7.500) = 7638 
    [ 7.500, 10.000) = 1222 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     23.912 ms/op
     p(99.9990) =     26.136 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.342 ± 3.695  ops/ms
ClientPb.existUser                       thrpt       3   9.926 ± 1.753  ops/ms
ClientPb.getUser                         thrpt       3   9.421 ± 3.582  ops/ms
ClientPb.listUser                        thrpt       3   8.068 ± 3.214  ops/ms
ClientPb.createUser                       avgt       3   3.295 ± 0.622   ms/op
ClientPb.existUser                        avgt       3   3.253 ± 1.286   ms/op
ClientPb.getUser                          avgt       3   3.380 ± 0.889   ms/op
ClientPb.listUser                         avgt       3   4.036 ± 2.419   ms/op
ClientPb.createUser                     sample  282193   3.402 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.518           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.203           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.855           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.494           ms/op
ClientPb.existUser                      sample  293379   3.271 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.249           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.827           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.477           ms/op
ClientPb.getUser                        sample  283202   3.386 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.027           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.038           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.811           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.329           ms/op
ClientPb.listUser                       sample  240656   3.990 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.024           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.804           ms/op
