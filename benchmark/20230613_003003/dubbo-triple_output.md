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
# Warmup Iteration   1: 1.573 ops/ms
# Warmup Iteration   2: 4.032 ops/ms
# Warmup Iteration   3: 7.200 ops/ms
Iteration   1: 7.426 ops/ms
Iteration   2: 7.911 ops/ms
Iteration   3: 7.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.679 ±(99.9%) 4.438 ops/ms [Average]
  (min, avg, max) = (7.426, 7.679, 7.911), stdev = 0.243
  CI (99.9%): [3.241, 12.117] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.221 ops/ms
# Warmup Iteration   2: 6.687 ops/ms
# Warmup Iteration   3: 7.928 ops/ms
Iteration   1: 8.101 ops/ms
Iteration   2: 8.425 ops/ms
Iteration   3: 8.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.345 ±(99.9%) 3.948 ops/ms [Average]
  (min, avg, max) = (8.101, 8.345, 8.511), stdev = 0.216
  CI (99.9%): [4.398, 12.293] (assumes normal distribution)


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
# Warmup Iteration   1: 2.047 ops/ms
# Warmup Iteration   2: 6.758 ops/ms
# Warmup Iteration   3: 7.674 ops/ms
Iteration   1: 7.309 ops/ms
Iteration   2: 8.070 ops/ms
Iteration   3: 8.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.837 ±(99.9%) 8.360 ops/ms [Average]
  (min, avg, max) = (7.309, 7.837, 8.133), stdev = 0.458
  CI (99.9%): [≈ 0, 16.197] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 5.902 ops/ms
# Warmup Iteration   3: 6.596 ops/ms
Iteration   1: 6.642 ops/ms
Iteration   2: 6.857 ops/ms
Iteration   3: 6.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.744 ±(99.9%) 1.968 ops/ms [Average]
  (min, avg, max) = (6.642, 6.744, 6.857), stdev = 0.108
  CI (99.9%): [4.775, 8.712] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.857 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.374 ±(99.9%) 0.007 ms/op
Iteration   1: 4.017 ±(99.9%) 0.011 ms/op
Iteration   2: 4.010 ±(99.9%) 0.015 ms/op
Iteration   3: 3.997 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.008 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (3.997, 4.008, 4.017), stdev = 0.010
  CI (99.9%): [3.820, 4.196] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.767 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.009 ms/op
Iteration   1: 3.844 ±(99.9%) 0.003 ms/op
Iteration   2: 3.834 ±(99.9%) 0.004 ms/op
Iteration   3: 3.835 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.838 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (3.834, 3.838, 3.844), stdev = 0.005
  CI (99.9%): [3.738, 3.938] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.836 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.950 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.897 ±(99.9%) 0.010 ms/op
Iteration   2: 3.892 ±(99.9%) 0.006 ms/op
Iteration   3: 3.821 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.870 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (3.821, 3.870, 3.897), stdev = 0.043
  CI (99.9%): [3.093, 4.648] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.804 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.424 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.750 ±(99.9%) 0.008 ms/op
Iteration   1: 4.568 ±(99.9%) 0.014 ms/op
Iteration   2: 4.690 ±(99.9%) 0.011 ms/op
Iteration   3: 4.474 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.577 ±(99.9%) 1.980 ms/op [Average]
  (min, avg, max) = (4.474, 4.577, 4.690), stdev = 0.109
  CI (99.9%): [2.597, 6.558] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.871 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 5.606 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.510 ±(99.9%) 0.019 ms/op
Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   7.684 ms/op
                 createUser·p0.999:  13.588 ms/op
                 createUser·p0.9999: 24.214 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   2: 4.170 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.855 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   7.979 ms/op
                 createUser·p0.999:  23.003 ms/op
                 createUser·p0.9999: 31.763 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   3: 4.053 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.982 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  26.514 ms/op
                 createUser·p0.9999: 29.192 ms/op
                 createUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235939
  mean =      4.067 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 217965 
    [ 5.000,  7.500) = 15258 
    [ 7.500, 10.000) = 2107 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     29.257 ms/op
     p(99.9990) =     33.901 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.641 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.771 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.012 ms/op
Iteration   1: 3.842 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  24.281 ms/op
                 existUser·p0.9999: 28.093 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   2: 3.815 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.150 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  14.683 ms/op
                 existUser·p0.9999: 27.651 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.940 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.915 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  14.828 ms/op
                 existUser·p0.9999: 27.165 ms/op
                 existUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248274
  mean =      3.865 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 164 
    [ 2.500,  5.000) = 237577 
    [ 5.000,  7.500) = 8536 
    [ 7.500, 10.000) = 1341 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 166 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     29.312 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 14.237 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.099 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.018 ms/op
Iteration   1: 4.285 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   6.930 ms/op
                 getUser·p0.99:   9.781 ms/op
                 getUser·p0.999:  24.914 ms/op
                 getUser·p0.9999: 26.872 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   2: 4.145 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   8.798 ms/op
                 getUser·p0.999:  20.021 ms/op
                 getUser·p0.9999: 27.609 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   3: 4.306 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.978 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.104 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   7.668 ms/op
                 getUser·p0.999:  13.239 ms/op
                 getUser·p0.9999: 35.652 ms/op
                 getUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226138
  mean =      4.244 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 205765 
    [ 5.000,  7.500) = 14850 
    [ 7.500, 10.000) = 4167 
    [10.000, 12.500) = 845 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     23.396 ms/op
     p(99.9900) =     34.563 ms/op
     p(99.9990) =     37.142 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 15.638 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 6.073 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.883 ±(99.9%) 0.016 ms/op
Iteration   1: 4.994 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  30.793 ms/op
                 listUser·p0.9999: 36.504 ms/op
                 listUser·p1.00:   37.749 ms/op

Iteration   2: 4.821 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  18.961 ms/op
                 listUser·p0.9999: 26.274 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   3: 4.750 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 24.874 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197611
  mean =      4.853 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 157296 
    [ 5.000,  7.500) = 35923 
    [ 7.500, 10.000) = 2891 
    [10.000, 12.500) = 918 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      2.134 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     21.375 ms/op
     p(99.9900) =     35.405 ms/op
     p(99.9990) =     37.301 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.679 ± 4.438  ops/ms
ClientPb.existUser                       thrpt       3   8.345 ± 3.948  ops/ms
ClientPb.getUser                         thrpt       3   7.837 ± 8.360  ops/ms
ClientPb.listUser                        thrpt       3   6.744 ± 1.968  ops/ms
ClientPb.createUser                       avgt       3   4.008 ± 0.188   ms/op
ClientPb.existUser                        avgt       3   3.838 ± 0.100   ms/op
ClientPb.getUser                          avgt       3   3.870 ± 0.777   ms/op
ClientPb.listUser                         avgt       3   4.577 ± 1.980   ms/op
ClientPb.createUser                     sample  235939   4.067 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.023           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.627           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.708           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.257           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948           ms/op
ClientPb.existUser                      sample  248274   3.865 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.444           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.828           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.591           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.426           ms/op
ClientPb.getUser                        sample  226138   4.244 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.663           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.028           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.396           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.563           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.159           ms/op
ClientPb.listUser                       sample  197611   4.853 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.134           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.372           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.375           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.405           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.749           ms/op
