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
# Warmup Iteration   1: 1.702 ops/ms
# Warmup Iteration   2: 4.332 ops/ms
# Warmup Iteration   3: 7.630 ops/ms
Iteration   1: 7.866 ops/ms
Iteration   2: 8.282 ops/ms
Iteration   3: 8.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.159 ±(99.9%) 4.641 ops/ms [Average]
  (min, avg, max) = (7.866, 8.159, 8.328), stdev = 0.254
  CI (99.9%): [3.518, 12.800] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.346 ops/ms
# Warmup Iteration   2: 7.411 ops/ms
# Warmup Iteration   3: 8.050 ops/ms
Iteration   1: 8.638 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 9.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.681 ±(99.9%) 5.592 ops/ms [Average]
  (min, avg, max) = (8.398, 8.681, 9.006), stdev = 0.307
  CI (99.9%): [3.089, 14.272] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.782 ops/ms
# Warmup Iteration   2: 8.037 ops/ms
# Warmup Iteration   3: 8.331 ops/ms
Iteration   1: 8.084 ops/ms
Iteration   2: 8.506 ops/ms
Iteration   3: 8.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.303 ±(99.9%) 3.852 ops/ms [Average]
  (min, avg, max) = (8.084, 8.303, 8.506), stdev = 0.211
  CI (99.9%): [4.451, 12.154] (assumes normal distribution)


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
# Warmup Iteration   1: 2.264 ops/ms
# Warmup Iteration   2: 6.374 ops/ms
# Warmup Iteration   3: 7.194 ops/ms
Iteration   1: 7.173 ops/ms
Iteration   2: 7.276 ops/ms
Iteration   3: 7.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.341 ±(99.9%) 3.809 ops/ms [Average]
  (min, avg, max) = (7.173, 7.341, 7.575), stdev = 0.209
  CI (99.9%): [3.532, 11.150] (assumes normal distribution)


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
# Warmup Iteration   1: 11.473 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.007 ms/op
Iteration   1: 3.608 ±(99.9%) 0.012 ms/op
Iteration   2: 3.705 ±(99.9%) 0.006 ms/op
Iteration   3: 3.768 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.693 ±(99.9%) 1.472 ms/op [Average]
  (min, avg, max) = (3.608, 3.693, 3.768), stdev = 0.081
  CI (99.9%): [2.221, 5.166] (assumes normal distribution)


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
# Warmup Iteration   1: 9.936 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.004 ms/op
Iteration   1: 3.467 ±(99.9%) 0.010 ms/op
Iteration   2: 3.496 ±(99.9%) 0.007 ms/op
Iteration   3: 3.572 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.512 ±(99.9%) 0.993 ms/op [Average]
  (min, avg, max) = (3.467, 3.512, 3.572), stdev = 0.054
  CI (99.9%): [2.519, 4.505] (assumes normal distribution)


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
# Warmup Iteration   1: 12.287 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.009 ms/op
Iteration   1: 3.693 ±(99.9%) 0.009 ms/op
Iteration   2: 3.694 ±(99.9%) 0.007 ms/op
Iteration   3: 3.809 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.732 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (3.693, 3.732, 3.809), stdev = 0.067
  CI (99.9%): [2.514, 4.950] (assumes normal distribution)


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
# Warmup Iteration   1: 13.966 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.605 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.715 ±(99.9%) 0.012 ms/op
Iteration   1: 4.594 ±(99.9%) 0.008 ms/op
Iteration   2: 4.442 ±(99.9%) 0.013 ms/op
Iteration   3: 4.178 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.405 ±(99.9%) 3.835 ms/op [Average]
  (min, avg, max) = (4.178, 4.405, 4.594), stdev = 0.210
  CI (99.9%): [0.570, 8.240] (assumes normal distribution)


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
# Warmup Iteration   1: 12.528 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.934 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.386 ±(99.9%) 0.018 ms/op
Iteration   1: 3.876 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.912 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  23.691 ms/op
                 createUser·p0.9999: 26.935 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   2: 3.741 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  24.920 ms/op
                 createUser·p0.9999: 28.261 ms/op
                 createUser·p1.00:   29.688 ms/op

Iteration   3: 3.739 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.993 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  17.882 ms/op
                 createUser·p0.9999: 32.462 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 253434
  mean =      3.784 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 757 
    [ 2.500,  5.000) = 244666 
    [ 5.000,  7.500) = 6482 
    [ 7.500, 10.000) = 922 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.952 ms/op
     p(99.9000) =     23.499 ms/op
     p(99.9900) =     31.533 ms/op
     p(99.9990) =     32.943 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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
# Warmup Iteration   1: 11.272 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.011 ms/op
Iteration   1: 3.881 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  22.694 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   2: 3.748 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.618 ms/op
                 existUser·p0.999:  19.169 ms/op
                 existUser·p0.9999: 29.506 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   3: 3.772 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.633 ms/op
                 existUser·p0.999:  29.398 ms/op
                 existUser·p0.9999: 34.212 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252685
  mean =      3.799 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1212 
    [ 2.500,  5.000) = 241343 
    [ 5.000,  7.500) = 8496 
    [ 7.500, 10.000) = 983 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     21.965 ms/op
     p(99.9900) =     32.169 ms/op
     p(99.9990) =     34.831 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 13.073 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.017 ms/op
Iteration   1: 3.983 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.763 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  20.864 ms/op
                 getUser·p0.9999: 24.013 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 4.037 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.883 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  9.978 ms/op
                 getUser·p0.9999: 26.285 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.866 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.915 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  25.603 ms/op
                 getUser·p0.9999: 28.410 ms/op
                 getUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242085
  mean =      3.961 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 231705 
    [ 5.000,  7.500) = 8675 
    [ 7.500, 10.000) = 1119 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 97 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     27.322 ms/op
     p(99.9990) =     28.743 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.738 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 5.181 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.565 ±(99.9%) 0.016 ms/op
Iteration   1: 4.605 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.908 ms/op
                 listUser·p0.99:   8.429 ms/op
                 listUser·p0.999:  24.427 ms/op
                 listUser·p0.9999: 26.593 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.514 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  17.245 ms/op
                 listUser·p0.9999: 21.383 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   3: 4.305 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  18.678 ms/op
                 listUser·p0.9999: 22.727 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 214548
  mean =      4.471 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 188734 
    [ 5.000,  7.500) = 22204 
    [ 7.500, 10.000) = 2807 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     20.000 ms/op
     p(99.9900) =     25.348 ms/op
     p(99.9990) =     28.217 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.159 ± 4.641  ops/ms
ClientPb.existUser                       thrpt       3   8.681 ± 5.592  ops/ms
ClientPb.getUser                         thrpt       3   8.303 ± 3.852  ops/ms
ClientPb.listUser                        thrpt       3   7.341 ± 3.809  ops/ms
ClientPb.createUser                       avgt       3   3.693 ± 1.472   ms/op
ClientPb.existUser                        avgt       3   3.512 ± 0.993   ms/op
ClientPb.getUser                          avgt       3   3.732 ± 1.218   ms/op
ClientPb.listUser                         avgt       3   4.405 ± 3.835   ms/op
ClientPb.createUser                     sample  253434   3.784 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.255           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.952           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.499           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.533           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.128           ms/op
ClientPb.existUser                      sample  252685   3.799 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.998           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.660           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.965           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.169           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.996           ms/op
ClientPb.getUser                        sample  242085   3.961 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.763           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.930           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.840           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.322           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.836           ms/op
ClientPb.listUser                       sample  214548   4.471 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.624           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.087           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.167           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.000           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.348           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
