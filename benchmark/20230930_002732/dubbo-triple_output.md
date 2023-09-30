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
# Warmup Iteration   1: 2.484 ops/ms
# Warmup Iteration   2: 5.590 ops/ms
# Warmup Iteration   3: 9.255 ops/ms
Iteration   1: 9.885 ops/ms
Iteration   2: 9.602 ops/ms
Iteration   3: 9.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.783 ±(99.9%) 2.859 ops/ms [Average]
  (min, avg, max) = (9.602, 9.783, 9.885), stdev = 0.157
  CI (99.9%): [6.923, 12.642] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.831 ops/ms
# Warmup Iteration   2: 9.445 ops/ms
# Warmup Iteration   3: 10.190 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 10.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.227 ±(99.9%) 4.750 ops/ms [Average]
  (min, avg, max) = (9.935, 10.227, 10.435), stdev = 0.260
  CI (99.9%): [5.477, 14.978] (assumes normal distribution)


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
# Warmup Iteration   1: 3.226 ops/ms
# Warmup Iteration   2: 8.870 ops/ms
# Warmup Iteration   3: 9.717 ops/ms
Iteration   1: 10.045 ops/ms
Iteration   2: 10.027 ops/ms
Iteration   3: 9.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.933 ±(99.9%) 3.241 ops/ms [Average]
  (min, avg, max) = (9.729, 9.933, 10.045), stdev = 0.178
  CI (99.9%): [6.692, 13.175] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.064 ops/ms
# Warmup Iteration   2: 7.833 ops/ms
# Warmup Iteration   3: 8.348 ops/ms
Iteration   1: 8.171 ops/ms
Iteration   2: 8.444 ops/ms
Iteration   3: 8.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.329 ±(99.9%) 2.579 ops/ms [Average]
  (min, avg, max) = (8.171, 8.329, 8.444), stdev = 0.141
  CI (99.9%): [5.749, 10.908] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.423 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.003 ms/op
Iteration   1: 3.181 ±(99.9%) 0.002 ms/op
Iteration   2: 3.262 ±(99.9%) 0.006 ms/op
Iteration   3: 3.234 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.225 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.181, 3.225, 3.262), stdev = 0.041
  CI (99.9%): [2.472, 3.979] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.479 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.004 ms/op
Iteration   1: 3.116 ±(99.9%) 0.002 ms/op
Iteration   2: 3.172 ±(99.9%) 0.004 ms/op
Iteration   3: 3.121 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.136 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.116, 3.136, 3.172), stdev = 0.031
  CI (99.9%): [2.566, 3.707] (assumes normal distribution)


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
# Warmup Iteration   1: 8.410 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.003 ms/op
Iteration   1: 3.237 ±(99.9%) 0.002 ms/op
Iteration   2: 3.130 ±(99.9%) 0.003 ms/op
Iteration   3: 3.242 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.203 ±(99.9%) 1.154 ms/op [Average]
  (min, avg, max) = (3.130, 3.203, 3.242), stdev = 0.063
  CI (99.9%): [2.050, 4.357] (assumes normal distribution)


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
# Warmup Iteration   1: 8.721 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.003 ms/op
Iteration   1: 3.785 ±(99.9%) 0.005 ms/op
Iteration   2: 3.722 ±(99.9%) 0.007 ms/op
Iteration   3: 3.774 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.761 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (3.722, 3.761, 3.785), stdev = 0.034
  CI (99.9%): [3.147, 4.374] (assumes normal distribution)


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
# Warmup Iteration   1: 8.454 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
Iteration   1: 3.223 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  9.878 ms/op
                 createUser·p0.9999: 19.598 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  17.158 ms/op
                 createUser·p0.9999: 21.243 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.370 ms/op
                 createUser·p0.999:  14.238 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297313
  mean =      3.225 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17482 
    [ 2.500,  5.000) = 275004 
    [ 5.000,  7.500) = 3925 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 6.854 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
Iteration   1: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  12.707 ms/op
                 existUser·p0.9999: 20.733 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.189 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  16.257 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  12.337 ms/op
                 existUser·p0.9999: 21.854 ms/op
                 existUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303788
  mean =      3.158 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15961 
    [ 2.500,  5.000) = 282407 
    [ 5.000,  7.500) = 4328 
    [ 7.500, 10.000) = 433 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     14.347 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.383 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 8.600 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
Iteration   1: 3.184 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.259 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 22.839 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   2: 3.336 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  19.351 ms/op
                 getUser·p0.9999: 22.820 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  14.609 ms/op
                 getUser·p0.9999: 22.268 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294393
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7625 
    [ 2.500,  5.000) = 281409 
    [ 5.000,  7.500) = 4323 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     17.518 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     23.418 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 8.733 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.011 ms/op
Iteration   1: 3.886 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.413 ms/op
                 listUser·p0.9999: 19.900 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   3: 3.828 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 18.044 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247918
  mean =      3.869 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 240218 
    [ 5.000,  7.500) = 6020 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 326 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.982 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.783 ± 2.859  ops/ms
ClientPb.existUser                       thrpt       3  10.227 ± 4.750  ops/ms
ClientPb.getUser                         thrpt       3   9.933 ± 3.241  ops/ms
ClientPb.listUser                        thrpt       3   8.329 ± 2.579  ops/ms
ClientPb.createUser                       avgt       3   3.225 ± 0.754   ms/op
ClientPb.existUser                        avgt       3   3.136 ± 0.571   ms/op
ClientPb.getUser                          avgt       3   3.203 ± 1.154   ms/op
ClientPb.listUser                         avgt       3   3.761 ± 0.613   ms/op
ClientPb.createUser                     sample  297313   3.225 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.951           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.539           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.238           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.414           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.887           ms/op
ClientPb.existUser                      sample  303788   3.158 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.266           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.347           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.348           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.495           ms/op
ClientPb.getUser                        sample  294393   3.259 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.606           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.576           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.518           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.774           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.790           ms/op
ClientPb.listUser                       sample  247918   3.869 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.982           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.385           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.298           ms/op
