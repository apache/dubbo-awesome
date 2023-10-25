# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.132 ops/ms
# Warmup Iteration   2: 4.835 ops/ms
# Warmup Iteration   3: 8.734 ops/ms
Iteration   1: 9.495 ops/ms
Iteration   2: 9.599 ops/ms
Iteration   3: 9.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.643 ±(99.9%) 3.186 ops/ms [Average]
  (min, avg, max) = (9.495, 9.643, 9.836), stdev = 0.175
  CI (99.9%): [6.457, 12.829] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.465 ops/ms
# Warmup Iteration   2: 9.151 ops/ms
# Warmup Iteration   3: 9.696 ops/ms
Iteration   1: 9.942 ops/ms
Iteration   2: 9.846 ops/ms
Iteration   3: 9.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.876 ±(99.9%) 1.037 ops/ms [Average]
  (min, avg, max) = (9.841, 9.876, 9.942), stdev = 0.057
  CI (99.9%): [8.839, 10.913] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.669 ops/ms
# Warmup Iteration   2: 8.716 ops/ms
# Warmup Iteration   3: 9.636 ops/ms
Iteration   1: 9.604 ops/ms
Iteration   2: 9.947 ops/ms
Iteration   3: 9.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.709 ±(99.9%) 3.781 ops/ms [Average]
  (min, avg, max) = (9.575, 9.709, 9.947), stdev = 0.207
  CI (99.9%): [5.928, 13.490] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.293 ops/ms
# Warmup Iteration   2: 7.571 ops/ms
# Warmup Iteration   3: 8.245 ops/ms
Iteration   1: 7.939 ops/ms
Iteration   2: 8.303 ops/ms
Iteration   3: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.187 ±(99.9%) 3.932 ops/ms [Average]
  (min, avg, max) = (7.939, 8.187, 8.320), stdev = 0.216
  CI (99.9%): [4.255, 12.120] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.604 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.003 ms/op
Iteration   1: 3.270 ±(99.9%) 0.004 ms/op
Iteration   2: 3.250 ±(99.9%) 0.003 ms/op
Iteration   3: 3.313 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.277 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.250, 3.277, 3.313), stdev = 0.032
  CI (99.9%): [2.692, 3.863] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.787 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.002 ms/op
Iteration   1: 3.224 ±(99.9%) 0.003 ms/op
Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
Iteration   3: 3.183 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.178 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.127, 3.178, 3.224), stdev = 0.049
  CI (99.9%): [2.291, 4.065] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.332 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.003 ms/op
Iteration   1: 3.340 ±(99.9%) 0.002 ms/op
Iteration   2: 3.296 ±(99.9%) 0.003 ms/op
Iteration   3: 3.215 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.283 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (3.215, 3.283, 3.340), stdev = 0.063
  CI (99.9%): [2.127, 4.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.293 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.004 ms/op
Iteration   1: 3.916 ±(99.9%) 0.006 ms/op
Iteration   2: 3.944 ±(99.9%) 0.004 ms/op
Iteration   3: 3.878 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.913 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.878, 3.913, 3.944), stdev = 0.033
  CI (99.9%): [3.307, 4.518] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.461 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.007 ms/op
Iteration   1: 3.329 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.782 ms/op
                 createUser·p0.999:  17.159 ms/op
                 createUser·p0.9999: 21.017 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 3.284 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.345 ms/op
                 createUser·p0.999:  17.443 ms/op
                 createUser·p0.9999: 25.314 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   3: 3.275 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 22.159 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291390
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11194 
    [ 2.500,  5.000) = 275207 
    [ 5.000,  7.500) = 4000 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     17.472 ms/op
     p(99.9900) =     24.258 ms/op
     p(99.9990) =     26.190 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.107 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
Iteration   1: 3.281 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.606 ms/op
                 existUser·p0.999:  16.564 ms/op
                 existUser·p0.9999: 21.315 ms/op
                 existUser·p1.00:   21.823 ms/op

Iteration   2: 3.179 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  16.292 ms/op
                 existUser·p0.9999: 24.314 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 3.277 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  20.460 ms/op
                 existUser·p0.9999: 31.924 ms/op
                 existUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295771
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13297 
    [ 2.500,  5.000) = 276832 
    [ 5.000,  7.500) = 4628 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     18.489 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.243 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.010 ms/op
Iteration   1: 3.237 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  17.962 ms/op
                 getUser·p0.9999: 22.683 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.280 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  14.598 ms/op
                 getUser·p0.9999: 22.823 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   3: 3.311 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  14.832 ms/op
                 getUser·p0.9999: 21.584 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292909
  mean =      3.275 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8399 
    [ 2.500,  5.000) = 278452 
    [ 5.000,  7.500) = 4802 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     15.419 ms/op
     p(99.9900) =     22.600 ms/op
     p(99.9990) =     23.825 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.812 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.012 ms/op
Iteration   1: 3.988 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.745 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 19.463 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.911 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.553 ms/op
                 listUser·p0.9999: 22.756 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 3.906 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.048 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.730 ms/op
                 listUser·p0.9999: 16.099 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244141
  mean =      3.934 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 237305 
    [ 5.000,  7.500) = 5149 
    [ 7.500, 10.000) = 855 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 459 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     19.254 ms/op
     p(99.9990) =     23.685 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.643 ± 3.186  ops/ms
ClientPb.existUser                       thrpt       3   9.876 ± 1.037  ops/ms
ClientPb.getUser                         thrpt       3   9.709 ± 3.781  ops/ms
ClientPb.listUser                        thrpt       3   8.187 ± 3.932  ops/ms
ClientPb.createUser                       avgt       3   3.277 ± 0.586   ms/op
ClientPb.existUser                        avgt       3   3.178 ± 0.887   ms/op
ClientPb.getUser                          avgt       3   3.283 ± 1.156   ms/op
ClientPb.listUser                         avgt       3   3.913 ± 0.605   ms/op
ClientPb.createUser                     sample  291390   3.296 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.034           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.472           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.258           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.804           ms/op
ClientPb.existUser                      sample  295771   3.245 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.890           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.489           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.211           ms/op
ClientPb.getUser                        sample  292909   3.275 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.030           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.419           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.600           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.921           ms/op
ClientPb.listUser                       sample  244141   3.934 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.968           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.418           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.254           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.921           ms/op
