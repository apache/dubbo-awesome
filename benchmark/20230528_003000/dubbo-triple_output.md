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
# Warmup Iteration   1: 2.302 ops/ms
# Warmup Iteration   2: 6.146 ops/ms
# Warmup Iteration   3: 9.169 ops/ms
Iteration   1: 9.885 ops/ms
Iteration   2: 10.261 ops/ms
Iteration   3: 9.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.048 ±(99.9%) 3.523 ops/ms [Average]
  (min, avg, max) = (9.885, 10.048, 10.261), stdev = 0.193
  CI (99.9%): [6.525, 13.570] (assumes normal distribution)


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
# Warmup Iteration   1: 3.396 ops/ms
# Warmup Iteration   2: 9.020 ops/ms
# Warmup Iteration   3: 9.745 ops/ms
Iteration   1: 10.001 ops/ms
Iteration   2: 10.024 ops/ms
Iteration   3: 9.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.985 ±(99.9%) 0.901 ops/ms [Average]
  (min, avg, max) = (9.929, 9.985, 10.024), stdev = 0.049
  CI (99.9%): [9.084, 10.886] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.046 ops/ms
# Warmup Iteration   2: 8.693 ops/ms
# Warmup Iteration   3: 9.440 ops/ms
Iteration   1: 10.102 ops/ms
Iteration   2: 10.083 ops/ms
Iteration   3: 9.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.970 ±(99.9%) 3.860 ops/ms [Average]
  (min, avg, max) = (9.726, 9.970, 10.102), stdev = 0.212
  CI (99.9%): [6.110, 13.831] (assumes normal distribution)


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
# Warmup Iteration   1: 2.970 ops/ms
# Warmup Iteration   2: 7.428 ops/ms
# Warmup Iteration   3: 8.067 ops/ms
Iteration   1: 8.408 ops/ms
Iteration   2: 8.332 ops/ms
Iteration   3: 8.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.440 ±(99.9%) 2.301 ops/ms [Average]
  (min, avg, max) = (8.332, 8.440, 8.578), stdev = 0.126
  CI (99.9%): [6.139, 10.740] (assumes normal distribution)


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
# Warmup Iteration   1: 8.794 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.004 ms/op
Iteration   1: 3.234 ±(99.9%) 0.007 ms/op
Iteration   2: 3.207 ±(99.9%) 0.005 ms/op
Iteration   3: 3.219 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.220 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (3.207, 3.220, 3.234), stdev = 0.014
  CI (99.9%): [2.967, 3.474] (assumes normal distribution)


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
# Warmup Iteration   1: 7.565 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.004 ms/op
Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
Iteration   3: 3.064 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.046 ±(99.9%) 0.357 ms/op [Average]
  (min, avg, max) = (3.025, 3.046, 3.064), stdev = 0.020
  CI (99.9%): [2.689, 3.403] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.247 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.004 ms/op
Iteration   1: 3.335 ±(99.9%) 0.005 ms/op
Iteration   2: 3.207 ±(99.9%) 0.005 ms/op
Iteration   3: 3.252 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.265 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (3.207, 3.265, 3.335), stdev = 0.065
  CI (99.9%): [2.078, 4.452] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.706 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.004 ms/op
Iteration   1: 3.750 ±(99.9%) 0.011 ms/op
Iteration   2: 3.850 ±(99.9%) 0.008 ms/op
Iteration   3: 3.877 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.826 ±(99.9%) 1.230 ms/op [Average]
  (min, avg, max) = (3.750, 3.826, 3.877), stdev = 0.067
  CI (99.9%): [2.596, 5.056] (assumes normal distribution)


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
# Warmup Iteration   1: 8.146 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.009 ms/op
Iteration   1: 3.200 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  21.006 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  13.320 ms/op
                 createUser·p0.9999: 23.697 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  10.617 ms/op
                 createUser·p0.9999: 19.626 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298780
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19053 
    [ 2.500,  5.000) = 274437 
    [ 5.000,  7.500) = 4446 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.978 ms/op
     p(99.9900) =     24.297 ms/op
     p(99.9990) =     24.937 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.253 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.008 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  9.424 ms/op
                 existUser·p0.9999: 21.467 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 28.255 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   3: 3.261 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.981 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 22.878 ms/op
                 existUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302444
  mean =      3.172 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28394 
    [ 2.500,  5.000) = 270154 
    [ 5.000,  7.500) = 3296 
    [ 7.500, 10.000) = 310 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =      9.350 ms/op
     p(99.9900) =     26.485 ms/op
     p(99.9990) =     28.540 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 9.353 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.010 ms/op
Iteration   1: 3.219 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.376 ms/op
                 getUser·p0.999:  16.564 ms/op
                 getUser·p0.9999: 20.222 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.326 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  17.560 ms/op
                 getUser·p0.9999: 22.557 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.507 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  15.933 ms/op
                 getUser·p0.9999: 24.999 ms/op
                 getUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290999
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18123 
    [ 2.500,  5.000) = 265645 
    [ 5.000,  7.500) = 6338 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     24.275 ms/op
     p(99.9990) =     25.903 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 9.406 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.012 ms/op
Iteration   1: 3.893 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 25.749 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   2: 3.767 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 14.893 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 18.570 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249869
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 240858 
    [ 5.000,  7.500) = 6852 
    [ 7.500, 10.000) = 1314 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     27.214 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.048 ± 3.523  ops/ms
ClientPb.existUser                       thrpt       3   9.985 ± 0.901  ops/ms
ClientPb.getUser                         thrpt       3   9.970 ± 3.860  ops/ms
ClientPb.listUser                        thrpt       3   8.440 ± 2.301  ops/ms
ClientPb.createUser                       avgt       3   3.220 ± 0.253   ms/op
ClientPb.existUser                        avgt       3   3.046 ± 0.357   ms/op
ClientPb.getUser                          avgt       3   3.265 ± 1.187   ms/op
ClientPb.listUser                         avgt       3   3.826 ± 1.230   ms/op
ClientPb.createUser                     sample  298780   3.212 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.675           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.297           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.969           ms/op
ClientPb.existUser                      sample  302444   3.172 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.616           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.177           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.350           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.485           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.836           ms/op
ClientPb.getUser                        sample  290999   3.297 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.384           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.286           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.275           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.082           ms/op
ClientPb.listUser                       sample  249869   3.840 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.305           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.615           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.133           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.591           ms/op
