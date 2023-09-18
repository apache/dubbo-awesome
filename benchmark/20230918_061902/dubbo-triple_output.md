# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 5.583 ops/ms
# Warmup Iteration   3: 8.589 ops/ms
Iteration   1: 9.140 ops/ms
Iteration   2: 8.984 ops/ms
Iteration   3: 9.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.091 ±(99.9%) 1.696 ops/ms [Average]
  (min, avg, max) = (8.984, 9.091, 9.150), stdev = 0.093
  CI (99.9%): [7.395, 10.788] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.085 ops/ms
# Warmup Iteration   2: 8.820 ops/ms
# Warmup Iteration   3: 9.438 ops/ms
Iteration   1: 9.706 ops/ms
Iteration   2: 9.626 ops/ms
Iteration   3: 9.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.699 ±(99.9%) 1.274 ops/ms [Average]
  (min, avg, max) = (9.626, 9.699, 9.765), stdev = 0.070
  CI (99.9%): [8.425, 10.973] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.956 ops/ms
# Warmup Iteration   2: 8.702 ops/ms
# Warmup Iteration   3: 9.138 ops/ms
Iteration   1: 9.085 ops/ms
Iteration   2: 9.159 ops/ms
Iteration   3: 9.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.159 ±(99.9%) 1.342 ops/ms [Average]
  (min, avg, max) = (9.085, 9.159, 9.232), stdev = 0.074
  CI (99.9%): [7.816, 10.501] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.733 ops/ms
# Warmup Iteration   2: 7.164 ops/ms
# Warmup Iteration   3: 7.543 ops/ms
Iteration   1: 7.697 ops/ms
Iteration   2: 7.817 ops/ms
Iteration   3: 7.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.797 ±(99.9%) 1.687 ops/ms [Average]
  (min, avg, max) = (7.697, 7.797, 7.878), stdev = 0.092
  CI (99.9%): [6.110, 9.484] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.120 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.003 ms/op
Iteration   1: 3.441 ±(99.9%) 0.004 ms/op
Iteration   2: 3.521 ±(99.9%) 0.005 ms/op
Iteration   3: 3.456 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.473 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (3.441, 3.473, 3.521), stdev = 0.042
  CI (99.9%): [2.700, 4.246] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.683 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.004 ms/op
Iteration   1: 3.282 ±(99.9%) 0.006 ms/op
Iteration   2: 3.365 ±(99.9%) 0.004 ms/op
Iteration   3: 3.303 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.317 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (3.282, 3.317, 3.365), stdev = 0.044
  CI (99.9%): [2.522, 4.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.094 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.004 ms/op
Iteration   1: 3.503 ±(99.9%) 0.005 ms/op
Iteration   2: 3.385 ±(99.9%) 0.005 ms/op
Iteration   3: 3.476 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.455 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.385, 3.455, 3.503), stdev = 0.062
  CI (99.9%): [2.323, 4.586] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.948 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.341 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.006 ms/op
Iteration   1: 4.004 ±(99.9%) 0.011 ms/op
Iteration   2: 4.056 ±(99.9%) 0.008 ms/op
Iteration   3: 4.082 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.047 ±(99.9%) 0.732 ms/op [Average]
  (min, avg, max) = (4.004, 4.047, 4.082), stdev = 0.040
  CI (99.9%): [3.316, 4.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.323 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.009 ms/op
Iteration   1: 3.443 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 3.459 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  16.489 ms/op
                 createUser·p0.9999: 19.701 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   3: 3.480 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  17.300 ms/op
                 createUser·p0.9999: 24.376 ms/op
                 createUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277202
  mean =      3.460 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6327 
    [ 2.500,  5.000) = 265920 
    [ 5.000,  7.500) = 3939 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 189 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     17.098 ms/op
     p(99.9900) =     22.947 ms/op
     p(99.9990) =     25.159 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.092 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.008 ms/op
Iteration   1: 3.268 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  12.060 ms/op
                 existUser·p0.9999: 20.913 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.451 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.544 ms/op
                 existUser·p0.999:  20.966 ms/op
                 existUser·p0.9999: 23.930 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.372 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  20.321 ms/op
                 existUser·p0.9999: 27.725 ms/op
                 existUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285466
  mean =      3.362 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5503 
    [ 2.500,  5.000) = 274143 
    [ 5.000,  7.500) = 4616 
    [ 7.500, 10.000) = 572 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     26.655 ms/op
     p(99.9990) =     28.219 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.481 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.010 ms/op
Iteration   1: 3.556 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  20.020 ms/op
                 getUser·p0.9999: 23.888 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.496 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  21.164 ms/op
                 getUser·p0.9999: 23.653 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   3: 3.532 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  19.038 ms/op
                 getUser·p0.9999: 32.799 ms/op
                 getUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272158
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2946 
    [ 2.500,  5.000) = 263462 
    [ 5.000,  7.500) = 4718 
    [ 7.500, 10.000) = 500 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     29.786 ms/op
     p(99.9990) =     32.866 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.786 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.012 ms/op
Iteration   1: 4.133 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  19.366 ms/op
                 listUser·p0.9999: 24.355 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   2: 4.126 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  15.244 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   3: 4.079 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  15.860 ms/op
                 listUser·p0.9999: 17.743 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233306
  mean =      4.113 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 224361 
    [ 5.000,  7.500) = 7027 
    [ 7.500, 10.000) = 985 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 360 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     25.122 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.091 ± 1.696  ops/ms
ClientPb.existUser                       thrpt       3   9.699 ± 1.274  ops/ms
ClientPb.getUser                         thrpt       3   9.159 ± 1.342  ops/ms
ClientPb.listUser                        thrpt       3   7.797 ± 1.687  ops/ms
ClientPb.createUser                       avgt       3   3.473 ± 0.773   ms/op
ClientPb.existUser                        avgt       3   3.317 ± 0.794   ms/op
ClientPb.getUser                          avgt       3   3.455 ± 1.132   ms/op
ClientPb.listUser                         avgt       3   4.047 ± 0.732   ms/op
ClientPb.createUser                     sample  277202   3.460 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.978           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.098           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.947           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.756           ms/op
ClientPb.existUser                      sample  285466   3.362 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.980           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.956           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.655           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.639           ms/op
ClientPb.getUser                        sample  272158   3.528 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.412           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.431           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.786           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.899           ms/op
ClientPb.listUser                       sample  233306   4.113 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.661           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.925           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.069           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.492           ms/op
