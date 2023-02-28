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
# Warmup Iteration   1: 1.071 ops/ms
# Warmup Iteration   2: 2.575 ops/ms
# Warmup Iteration   3: 5.254 ops/ms
Iteration   1: 5.464 ops/ms
Iteration   2: 5.625 ops/ms
Iteration   3: 5.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.648 ±(99.9%) 3.584 ops/ms [Average]
  (min, avg, max) = (5.464, 5.648, 5.855), stdev = 0.196
  CI (99.9%): [2.064, 9.233] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 4.805 ops/ms
# Warmup Iteration   3: 5.631 ops/ms
Iteration   1: 5.849 ops/ms
Iteration   2: 5.960 ops/ms
Iteration   3: 5.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.874 ±(99.9%) 1.414 ops/ms [Average]
  (min, avg, max) = (5.811, 5.874, 5.960), stdev = 0.078
  CI (99.9%): [4.459, 7.288] (assumes normal distribution)


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
# Warmup Iteration   1: 1.435 ops/ms
# Warmup Iteration   2: 4.492 ops/ms
# Warmup Iteration   3: 5.780 ops/ms
Iteration   1: 5.771 ops/ms
Iteration   2: 5.732 ops/ms
Iteration   3: 5.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.758 ±(99.9%) 0.402 ops/ms [Average]
  (min, avg, max) = (5.732, 5.758, 5.771), stdev = 0.022
  CI (99.9%): [5.356, 6.159] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.506 ops/ms
# Warmup Iteration   2: 4.072 ops/ms
# Warmup Iteration   3: 4.637 ops/ms
Iteration   1: 5.024 ops/ms
Iteration   2: 4.761 ops/ms
Iteration   3: 4.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.916 ±(99.9%) 2.514 ops/ms [Average]
  (min, avg, max) = (4.761, 4.916, 5.024), stdev = 0.138
  CI (99.9%): [2.402, 7.431] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.286 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 7.138 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.935 ±(99.9%) 0.016 ms/op
Iteration   1: 5.555 ±(99.9%) 0.012 ms/op
Iteration   2: 5.957 ±(99.9%) 0.012 ms/op
Iteration   3: 5.748 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.753 ±(99.9%) 3.662 ms/op [Average]
  (min, avg, max) = (5.555, 5.753, 5.957), stdev = 0.201
  CI (99.9%): [2.091, 9.416] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.879 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.474 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.395 ±(99.9%) 0.010 ms/op
Iteration   1: 5.277 ±(99.9%) 0.013 ms/op
Iteration   2: 5.324 ±(99.9%) 0.010 ms/op
Iteration   3: 5.137 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.246 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (5.137, 5.246, 5.324), stdev = 0.098
  CI (99.9%): [3.464, 7.028] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.413 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.206 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.679 ±(99.9%) 0.008 ms/op
Iteration   1: 5.613 ±(99.9%) 0.009 ms/op
Iteration   2: 5.631 ±(99.9%) 0.009 ms/op
Iteration   3: 5.361 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.535 ±(99.9%) 2.755 ms/op [Average]
  (min, avg, max) = (5.361, 5.535, 5.631), stdev = 0.151
  CI (99.9%): [2.781, 8.290] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.822 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.682 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.635 ±(99.9%) 0.016 ms/op
Iteration   1: 6.445 ±(99.9%) 0.013 ms/op
Iteration   2: 6.423 ±(99.9%) 0.017 ms/op
Iteration   3: 6.506 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.458 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (6.423, 6.458, 6.506), stdev = 0.043
  CI (99.9%): [5.675, 7.241] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.354 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 8.238 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.268 ±(99.9%) 0.028 ms/op
Iteration   1: 5.617 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   6.955 ms/op
                 createUser·p0.95:   7.791 ms/op
                 createUser·p0.99:   10.732 ms/op
                 createUser·p0.999:  20.185 ms/op
                 createUser·p0.9999: 29.795 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   2: 5.309 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.535 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.652 ms/op
                 createUser·p0.95:   7.094 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  13.657 ms/op
                 createUser·p0.9999: 29.386 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   3: 5.626 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.384 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   7.094 ms/op
                 createUser·p0.95:   8.086 ms/op
                 createUser·p0.99:   10.852 ms/op
                 createUser·p0.999:  27.468 ms/op
                 createUser·p0.9999: 32.145 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174120
  mean =      5.513 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 68357 
    [ 5.000,  7.500) = 95902 
    [ 7.500, 10.000) = 7969 
    [10.000, 12.500) = 1191 
    [12.500, 15.000) = 378 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     18.346 ms/op
     p(99.9900) =     30.840 ms/op
     p(99.9990) =     32.695 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.805 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 7.212 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 5.591 ±(99.9%) 0.020 ms/op
Iteration   1: 5.340 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.791 ms/op
                 existUser·p0.95:   7.840 ms/op
                 existUser·p0.99:   11.469 ms/op
                 existUser·p0.999:  15.468 ms/op
                 existUser·p0.9999: 26.575 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   2: 5.325 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.660 ms/op
                 existUser·p0.99:   11.354 ms/op
                 existUser·p0.999:  21.954 ms/op
                 existUser·p0.9999: 25.133 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 5.236 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.075 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.463 ms/op
                 existUser·p0.95:   7.389 ms/op
                 existUser·p0.99:   10.273 ms/op
                 existUser·p0.999:  21.725 ms/op
                 existUser·p0.9999: 25.155 ms/op
                 existUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180988
  mean =      5.300 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 97456 
    [ 5.000,  7.500) = 73459 
    [ 7.500, 10.000) = 7290 
    [10.000, 12.500) = 1684 
    [12.500, 15.000) = 653 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     27.305 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.951 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 7.276 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.807 ±(99.9%) 0.023 ms/op
Iteration   1: 5.777 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   5.497 ms/op
                 getUser·p0.90:   7.340 ms/op
                 getUser·p0.95:   8.143 ms/op
                 getUser·p0.99:   11.485 ms/op
                 getUser·p0.999:  22.249 ms/op
                 getUser·p0.9999: 24.737 ms/op
                 getUser·p1.00:   27.066 ms/op

Iteration   2: 5.637 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.079 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.815 ms/op
                 getUser·p0.99:   10.174 ms/op
                 getUser·p0.999:  21.889 ms/op
                 getUser·p0.9999: 25.766 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   3: 5.448 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.666 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.742 ms/op
                 getUser·p0.95:   7.471 ms/op
                 getUser·p0.99:   10.224 ms/op
                 getUser·p0.999:  13.555 ms/op
                 getUser·p0.9999: 27.699 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170786
  mean =      5.618 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 59509 
    [ 5.000,  7.500) = 100258 
    [ 7.500, 10.000) = 8694 
    [10.000, 12.500) = 1543 
    [12.500, 15.000) = 378 
    [15.000, 17.500) = 204 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     19.839 ms/op
     p(99.9900) =     26.537 ms/op
     p(99.9990) =     28.602 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 20.462 ±(99.9%) 0.384 ms/op
# Warmup Iteration   2: 8.429 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.702 ±(99.9%) 0.030 ms/op
Iteration   1: 6.330 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.620 ms/op
                 listUser·p0.999:  27.736 ms/op
                 listUser·p0.9999: 29.973 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   2: 6.632 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   6.234 ms/op
                 listUser·p0.90:   8.307 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   13.420 ms/op
                 listUser·p0.999:  29.196 ms/op
                 listUser·p0.9999: 31.141 ms/op
                 listUser·p1.00:   32.506 ms/op

Iteration   3: 6.606 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   6.234 ms/op
                 listUser·p0.90:   8.143 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   12.648 ms/op
                 listUser·p0.999:  23.069 ms/op
                 listUser·p0.9999: 29.403 ms/op
                 listUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147197
  mean =      6.520 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 7419 
    [ 5.000,  7.500) = 117466 
    [ 7.500, 10.000) = 17996 
    [10.000, 12.500) = 2854 
    [12.500, 15.000) = 726 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 139 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.494 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      8.053 ms/op
     p(95.0000) =      9.175 ms/op
     p(99.0000) =     12.468 ms/op
     p(99.9000) =     27.879 ms/op
     p(99.9900) =     30.549 ms/op
     p(99.9990) =     32.166 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.648 ± 3.584  ops/ms
ClientPb.existUser                       thrpt       3   5.874 ± 1.414  ops/ms
ClientPb.getUser                         thrpt       3   5.758 ± 0.402  ops/ms
ClientPb.listUser                        thrpt       3   4.916 ± 2.514  ops/ms
ClientPb.createUser                       avgt       3   5.753 ± 3.662   ms/op
ClientPb.existUser                        avgt       3   5.246 ± 1.782   ms/op
ClientPb.getUser                          avgt       3   5.535 ± 2.755   ms/op
ClientPb.listUser                         avgt       3   6.458 ± 0.783   ms/op
ClientPb.createUser                     sample  174120   5.513 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.865           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.651           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.093           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.346           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.840           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.768           ms/op
ClientPb.existUser                      sample  180988   5.300 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.761           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.611           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.651           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.141           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.153           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.657           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  170786   5.618 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.858           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.349           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.947           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.873           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.732           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.839           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.537           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  147197   6.520 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.494           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.053           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.468           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.879           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.549           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.506           ms/op
