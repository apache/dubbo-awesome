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
# Warmup Iteration   1: 2.681 ops/ms
# Warmup Iteration   2: 6.735 ops/ms
# Warmup Iteration   3: 9.202 ops/ms
Iteration   1: 9.785 ops/ms
Iteration   2: 9.310 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.734 ±(99.9%) 7.306 ops/ms [Average]
  (min, avg, max) = (9.310, 9.734, 10.106), stdev = 0.400
  CI (99.9%): [2.427, 17.040] (assumes normal distribution)


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
# Warmup Iteration   1: 3.672 ops/ms
# Warmup Iteration   2: 9.179 ops/ms
# Warmup Iteration   3: 10.335 ops/ms
Iteration   1: 10.504 ops/ms
Iteration   2: 10.653 ops/ms
Iteration   3: 9.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.358 ±(99.9%) 7.097 ops/ms [Average]
  (min, avg, max) = (9.917, 10.358, 10.653), stdev = 0.389
  CI (99.9%): [3.261, 17.455] (assumes normal distribution)


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
# Warmup Iteration   1: 3.519 ops/ms
# Warmup Iteration   2: 9.266 ops/ms
# Warmup Iteration   3: 9.636 ops/ms
Iteration   1: 9.876 ops/ms
Iteration   2: 9.689 ops/ms
Iteration   3: 10.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.871 ±(99.9%) 3.281 ops/ms [Average]
  (min, avg, max) = (9.689, 9.871, 10.048), stdev = 0.180
  CI (99.9%): [6.590, 13.153] (assumes normal distribution)


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
# Warmup Iteration   1: 3.201 ops/ms
# Warmup Iteration   2: 7.617 ops/ms
# Warmup Iteration   3: 8.577 ops/ms
Iteration   1: 8.556 ops/ms
Iteration   2: 8.459 ops/ms
Iteration   3: 8.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.539 ±(99.9%) 1.312 ops/ms [Average]
  (min, avg, max) = (8.459, 8.539, 8.600), stdev = 0.072
  CI (99.9%): [7.226, 9.851] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.105 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.002 ms/op
Iteration   1: 3.236 ±(99.9%) 0.005 ms/op
Iteration   2: 3.190 ±(99.9%) 0.008 ms/op
Iteration   3: 3.133 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.186 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.133, 3.186, 3.236), stdev = 0.052
  CI (99.9%): [2.245, 4.127] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.773 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.004 ms/op
Iteration   1: 3.150 ±(99.9%) 0.005 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 3.168 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.126 ±(99.9%) 1.044 ms/op [Average]
  (min, avg, max) = (3.061, 3.126, 3.168), stdev = 0.057
  CI (99.9%): [2.083, 4.170] (assumes normal distribution)


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
# Warmup Iteration   1: 7.257 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.003 ms/op
Iteration   1: 3.223 ±(99.9%) 0.002 ms/op
Iteration   2: 3.181 ±(99.9%) 0.005 ms/op
Iteration   3: 3.172 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (3.172, 3.192, 3.223), stdev = 0.027
  CI (99.9%): [2.699, 3.685] (assumes normal distribution)


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
# Warmup Iteration   1: 8.226 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.007 ms/op
Iteration   1: 3.746 ±(99.9%) 0.007 ms/op
Iteration   2: 3.657 ±(99.9%) 0.011 ms/op
Iteration   3: 3.741 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.715 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (3.657, 3.715, 3.746), stdev = 0.050
  CI (99.9%): [2.807, 4.622] (assumes normal distribution)


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
# Warmup Iteration   1: 8.316 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.009 ms/op
Iteration   1: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  11.542 ms/op
                 createUser·p0.9999: 24.482 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.280 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.518 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  16.105 ms/op
                 createUser·p0.9999: 26.439 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   3: 3.198 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  10.767 ms/op
                 createUser·p0.9999: 16.778 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300319
  mean =      3.192 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30250 
    [ 2.500,  5.000) = 264842 
    [ 5.000,  7.500) = 4373 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     11.606 ms/op
     p(99.9900) =     25.755 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 7.493 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
Iteration   1: 3.283 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.614 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 26.583 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  12.714 ms/op
                 existUser·p0.9999: 21.855 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   3: 3.098 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  15.150 ms/op
                 existUser·p0.9999: 21.813 ms/op
                 existUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300775
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28322 
    [ 2.500,  5.000) = 266440 
    [ 5.000,  7.500) = 5304 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     24.868 ms/op
     p(99.9990) =     26.837 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 7.433 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.009 ms/op
Iteration   1: 3.399 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  17.177 ms/op
                 getUser·p0.9999: 23.579 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   2: 3.271 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  12.095 ms/op
                 getUser·p0.9999: 22.919 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.249 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.413 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290321
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20975 
    [ 2.500,  5.000) = 261283 
    [ 5.000,  7.500) = 7127 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     24.284 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 8.551 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.011 ms/op
Iteration   1: 3.861 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 17.554 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   2: 3.877 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 14.811 ms/op
                 listUser·p1.00:   14.877 ms/op

Iteration   3: 3.747 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  12.829 ms/op
                 listUser·p0.9999: 20.340 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250628
  mean =      3.827 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 240659 
    [ 5.000,  7.500) = 8107 
    [ 7.500, 10.000) = 1084 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.734 ± 7.306  ops/ms
ClientPb.existUser                       thrpt       3  10.358 ± 7.097  ops/ms
ClientPb.getUser                         thrpt       3   9.871 ± 3.281  ops/ms
ClientPb.listUser                        thrpt       3   8.539 ± 1.312  ops/ms
ClientPb.createUser                       avgt       3   3.186 ± 0.941   ms/op
ClientPb.existUser                        avgt       3   3.126 ± 1.044   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 0.493   ms/op
ClientPb.listUser                         avgt       3   3.715 ± 0.907   ms/op
ClientPb.createUser                     sample  300319   3.192 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.044           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.606           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.755           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.197           ms/op
ClientPb.existUser                      sample  300775   3.190 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.391           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.868           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  290321   3.305 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.040           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.980           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.729           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.200           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.969           ms/op
ClientPb.listUser                       sample  250628   3.827 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.612           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.809           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.103           ms/op
