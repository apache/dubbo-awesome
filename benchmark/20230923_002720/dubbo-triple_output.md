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
# Warmup Iteration   1: 1.481 ops/ms
# Warmup Iteration   2: 3.321 ops/ms
# Warmup Iteration   3: 6.672 ops/ms
Iteration   1: 7.501 ops/ms
Iteration   2: 7.719 ops/ms
Iteration   3: 7.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.669 ±(99.9%) 2.735 ops/ms [Average]
  (min, avg, max) = (7.501, 7.669, 7.788), stdev = 0.150
  CI (99.9%): [4.934, 10.405] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.248 ops/ms
# Warmup Iteration   2: 6.557 ops/ms
# Warmup Iteration   3: 7.930 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 7.826 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.049 ±(99.9%) 3.955 ops/ms [Average]
  (min, avg, max) = (7.826, 8.049, 8.259), stdev = 0.217
  CI (99.9%): [4.093, 12.004] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.487 ops/ms
# Warmup Iteration   2: 6.911 ops/ms
# Warmup Iteration   3: 7.214 ops/ms
Iteration   1: 7.785 ops/ms
Iteration   2: 7.615 ops/ms
Iteration   3: 7.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.715 ±(99.9%) 1.615 ops/ms [Average]
  (min, avg, max) = (7.615, 7.715, 7.785), stdev = 0.089
  CI (99.9%): [6.099, 9.330] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.138 ops/ms
# Warmup Iteration   2: 5.496 ops/ms
# Warmup Iteration   3: 6.189 ops/ms
Iteration   1: 6.107 ops/ms
Iteration   2: 6.563 ops/ms
Iteration   3: 6.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.464 ±(99.9%) 5.820 ops/ms [Average]
  (min, avg, max) = (6.107, 6.464, 6.722), stdev = 0.319
  CI (99.9%): [0.644, 12.284] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.056 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.006 ms/op
Iteration   1: 3.996 ±(99.9%) 0.005 ms/op
Iteration   2: 4.055 ±(99.9%) 0.006 ms/op
Iteration   3: 3.977 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.010 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.977, 4.010, 4.055), stdev = 0.041
  CI (99.9%): [3.270, 4.749] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.570 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.006 ms/op
Iteration   1: 3.925 ±(99.9%) 0.007 ms/op
Iteration   2: 3.853 ±(99.9%) 0.006 ms/op
Iteration   3: 3.931 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.903 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (3.853, 3.903, 3.931), stdev = 0.044
  CI (99.9%): [3.104, 4.702] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.015 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.687 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.007 ms/op
Iteration   1: 4.075 ±(99.9%) 0.005 ms/op
Iteration   2: 4.109 ±(99.9%) 0.006 ms/op
Iteration   3: 4.105 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.096 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (4.075, 4.096, 4.109), stdev = 0.018
  CI (99.9%): [3.760, 4.433] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.249 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.896 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.884 ±(99.9%) 0.006 ms/op
Iteration   1: 4.785 ±(99.9%) 0.008 ms/op
Iteration   2: 4.897 ±(99.9%) 0.010 ms/op
Iteration   3: 4.781 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.821 ±(99.9%) 1.208 ms/op [Average]
  (min, avg, max) = (4.781, 4.821, 4.897), stdev = 0.066
  CI (99.9%): [3.613, 6.030] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.412 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 5.031 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.485 ±(99.9%) 0.018 ms/op
Iteration   1: 4.097 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   8.233 ms/op
                 createUser·p0.999:  23.526 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   7.485 ms/op
                 createUser·p0.999:  13.575 ms/op
                 createUser·p0.9999: 29.692 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   3: 4.091 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   7.840 ms/op
                 createUser·p0.999:  29.062 ms/op
                 createUser·p0.9999: 32.346 ms/op
                 createUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234877
  mean =      4.083 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 493 
    [ 2.500,  5.000) = 215891 
    [ 5.000,  7.500) = 15697 
    [ 7.500, 10.000) = 1678 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     23.597 ms/op
     p(99.9900) =     31.278 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.122 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.013 ms/op
Iteration   1: 3.910 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   8.118 ms/op
                 existUser·p0.999:  21.141 ms/op
                 existUser·p0.9999: 30.828 ms/op
                 existUser·p1.00:   31.392 ms/op

Iteration   2: 3.986 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.772 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.702 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  14.809 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 4.055 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   7.623 ms/op
                 existUser·p0.999:  20.354 ms/op
                 existUser·p0.9999: 27.507 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240918
  mean =      3.982 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 820 
    [ 2.500,  5.000) = 221970 
    [ 5.000,  7.500) = 15098 
    [ 7.500, 10.000) = 1915 
    [10.000, 12.500) = 575 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     20.256 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     31.195 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.181 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.632 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.352 ±(99.9%) 0.019 ms/op
Iteration   1: 4.170 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   6.447 ms/op
                 getUser·p0.99:   9.863 ms/op
                 getUser·p0.999:  23.405 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   2: 4.105 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   8.348 ms/op
                 getUser·p0.999:  14.473 ms/op
                 getUser·p0.9999: 30.678 ms/op
                 getUser·p1.00:   31.850 ms/op

Iteration   3: 4.037 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.350 ms/op
                 getUser·p0.999:  28.663 ms/op
                 getUser·p0.9999: 31.928 ms/op
                 getUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233882
  mean =      4.103 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190 
    [ 2.500,  5.000) = 215083 
    [ 5.000,  7.500) = 14675 
    [ 7.500, 10.000) = 2449 
    [10.000, 12.500) = 883 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     23.531 ms/op
     p(99.9900) =     30.724 ms/op
     p(99.9990) =     32.298 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.071 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 5.661 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.006 ±(99.9%) 0.019 ms/op
Iteration   1: 4.929 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   9.917 ms/op
                 listUser·p0.999:  26.153 ms/op
                 listUser·p0.9999: 27.969 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   2: 4.774 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.472 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  18.251 ms/op
                 listUser·p0.9999: 19.887 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 4.725 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  17.653 ms/op
                 listUser·p0.9999: 19.807 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199520
  mean =      4.808 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 154882 
    [ 5.000,  7.500) = 38446 
    [ 7.500, 10.000) = 4722 
    [10.000, 12.500) = 798 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 100 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     19.119 ms/op
     p(99.9900) =     27.199 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.669 ± 2.735  ops/ms
ClientPb.existUser                       thrpt       3   8.049 ± 3.955  ops/ms
ClientPb.getUser                         thrpt       3   7.715 ± 1.615  ops/ms
ClientPb.listUser                        thrpt       3   6.464 ± 5.820  ops/ms
ClientPb.createUser                       avgt       3   4.010 ± 0.740   ms/op
ClientPb.existUser                        avgt       3   3.903 ± 0.799   ms/op
ClientPb.getUser                          avgt       3   4.096 ± 0.337   ms/op
ClientPb.listUser                         avgt       3   4.821 ± 1.208   ms/op
ClientPb.createUser                     sample  234877   4.083 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.961           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.817           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.758           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.597           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.278           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.423           ms/op
ClientPb.existUser                      sample  240918   3.982 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.590           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.710           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.873           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.256           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.507           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.392           ms/op
ClientPb.getUser                        sample  233882   4.103 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.065           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.634           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.531           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.724           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.801           ms/op
ClientPb.listUser                       sample  199520   4.808 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.327           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.372           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.119           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.199           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.574           ms/op
