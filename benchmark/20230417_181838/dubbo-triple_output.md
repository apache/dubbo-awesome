# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.504 ops/ms
# Warmup Iteration   2: 3.245 ops/ms
# Warmup Iteration   3: 6.152 ops/ms
Iteration   1: 7.134 ops/ms
Iteration   2: 7.748 ops/ms
Iteration   3: 7.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.540 ±(99.9%) 6.417 ops/ms [Average]
  (min, avg, max) = (7.134, 7.540, 7.748), stdev = 0.352
  CI (99.9%): [1.124, 13.957] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.392 ops/ms
# Warmup Iteration   2: 6.273 ops/ms
# Warmup Iteration   3: 7.267 ops/ms
Iteration   1: 7.882 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 7.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.869 ±(99.9%) 0.444 ops/ms [Average]
  (min, avg, max) = (7.841, 7.869, 7.884), stdev = 0.024
  CI (99.9%): [7.425, 8.313] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.216 ops/ms
# Warmup Iteration   2: 5.946 ops/ms
# Warmup Iteration   3: 7.764 ops/ms
Iteration   1: 7.768 ops/ms
Iteration   2: 7.606 ops/ms
Iteration   3: 7.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.584 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (7.377, 7.584, 7.768), stdev = 0.196
  CI (99.9%): [4.003, 11.164] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.808 ops/ms
# Warmup Iteration   2: 5.331 ops/ms
# Warmup Iteration   3: 6.285 ops/ms
Iteration   1: 6.119 ops/ms
Iteration   2: 6.334 ops/ms
Iteration   3: 6.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.411 ±(99.9%) 6.135 ops/ms [Average]
  (min, avg, max) = (6.119, 6.411, 6.779), stdev = 0.336
  CI (99.9%): [0.276, 12.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.692 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.145 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.589 ±(99.9%) 0.005 ms/op
Iteration   1: 4.096 ±(99.9%) 0.009 ms/op
Iteration   2: 3.999 ±(99.9%) 0.007 ms/op
Iteration   3: 3.972 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.022 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (3.972, 4.022, 4.096), stdev = 0.066
  CI (99.9%): [2.826, 5.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.876 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.761 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.011 ms/op
Iteration   1: 3.828 ±(99.9%) 0.013 ms/op
Iteration   2: 3.919 ±(99.9%) 0.013 ms/op
Iteration   3: 3.896 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.881 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (3.828, 3.881, 3.919), stdev = 0.047
  CI (99.9%): [3.015, 4.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.702 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.007 ms/op
Iteration   1: 4.290 ±(99.9%) 0.008 ms/op
Iteration   2: 4.165 ±(99.9%) 0.006 ms/op
Iteration   3: 3.939 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.131 ±(99.9%) 3.242 ms/op [Average]
  (min, avg, max) = (3.939, 4.131, 4.290), stdev = 0.178
  CI (99.9%): [0.889, 7.374] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.398 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 6.263 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.075 ±(99.9%) 0.016 ms/op
Iteration   1: 4.859 ±(99.9%) 0.012 ms/op
Iteration   2: 4.810 ±(99.9%) 0.017 ms/op
Iteration   3: 4.775 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.814 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (4.775, 4.814, 4.859), stdev = 0.042
  CI (99.9%): [4.046, 5.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.180 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 5.234 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.564 ±(99.9%) 0.019 ms/op
Iteration   1: 4.110 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   8.028 ms/op
                 createUser·p0.999:  24.452 ms/op
                 createUser·p0.9999: 28.326 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   2: 4.004 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.982 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.646 ms/op
                 createUser·p0.999:  12.147 ms/op
                 createUser·p0.9999: 31.458 ms/op
                 createUser·p1.00:   32.145 ms/op

Iteration   3: 4.163 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   8.364 ms/op
                 createUser·p0.999:  31.431 ms/op
                 createUser·p0.9999: 36.084 ms/op
                 createUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234486
  mean =      4.091 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 268 
    [ 2.500,  5.000) = 219431 
    [ 5.000,  7.500) = 12248 
    [ 7.500, 10.000) = 1887 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 84 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.722 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     24.527 ms/op
     p(99.9900) =     35.193 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.239 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.014 ms/op
Iteration   1: 3.987 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.150 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   7.000 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 30.145 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   2: 3.963 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   7.117 ms/op
                 existUser·p0.999:  14.632 ms/op
                 existUser·p0.9999: 30.573 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   3: 3.976 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   7.922 ms/op
                 existUser·p0.999:  34.603 ms/op
                 existUser·p0.9999: 44.625 ms/op
                 existUser·p1.00:   45.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241485
  mean =      3.975 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 229283 
    [ 5.000, 10.000) = 11390 
    [10.000, 15.000) = 506 
    [15.000, 20.000) = 79 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 57 
    [35.000, 40.000) = 37 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     43.057 ms/op
     p(99.9990) =     45.559 ms/op
     p(99.9999) =     45.679 ms/op
    p(100.0000) =     45.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.157 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.752 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.016 ms/op
Iteration   1: 4.136 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  26.149 ms/op
                 getUser·p0.9999: 28.010 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 4.154 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.464 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  12.538 ms/op
                 getUser·p0.9999: 30.386 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   3: 4.258 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.014 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   8.217 ms/op
                 getUser·p0.999:  20.673 ms/op
                 getUser·p0.9999: 40.337 ms/op
                 getUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229416
  mean =      4.182 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 209629 
    [ 5.000, 10.000) = 18940 
    [10.000, 15.000) = 559 
    [15.000, 20.000) = 47 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 148 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     38.470 ms/op
     p(99.9990) =     41.689 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.781 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 6.082 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.993 ±(99.9%) 0.017 ms/op
Iteration   1: 5.047 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   7.258 ms/op
                 listUser·p0.99:   9.661 ms/op
                 listUser·p0.999:  24.187 ms/op
                 listUser·p0.9999: 26.552 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 5.063 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   5.644 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  25.021 ms/op
                 listUser·p0.9999: 30.683 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   3: 5.007 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.699 ms/op
                 listUser·p0.50:   4.833 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  21.041 ms/op
                 listUser·p0.9999: 26.092 ms/op
                 listUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 190533
  mean =      5.039 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 125282 
    [ 5.000,  7.500) = 58596 
    [ 7.500, 10.000) = 5062 
    [10.000, 12.500) = 895 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     23.674 ms/op
     p(99.9900) =     29.615 ms/op
     p(99.9990) =     32.021 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.540 ± 6.417  ops/ms
ClientPb.existUser                       thrpt       3   7.869 ± 0.444  ops/ms
ClientPb.getUser                         thrpt       3   7.584 ± 3.580  ops/ms
ClientPb.listUser                        thrpt       3   6.411 ± 6.135  ops/ms
ClientPb.createUser                       avgt       3   4.022 ± 1.196   ms/op
ClientPb.existUser                        avgt       3   3.881 ± 0.866   ms/op
ClientPb.getUser                          avgt       3   4.131 ± 3.242   ms/op
ClientPb.listUser                         avgt       3   4.814 ± 0.769   ms/op
ClientPb.createUser                     sample  234486   4.091 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.722           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.782           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.527           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.193           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.224           ms/op
ClientPb.existUser                      sample  241485   3.975 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.299           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.400           ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.057           ms/op
ClientPb.existUser:existUser·p1.00      sample          45.679           ms/op
ClientPb.getUser                        sample  229416   4.182 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.953           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.767           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.290           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.709           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.470           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.878           ms/op
ClientPb.listUser                       sample  190533   5.039 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.399           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.644           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.601           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.674           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.615           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.080           ms/op
