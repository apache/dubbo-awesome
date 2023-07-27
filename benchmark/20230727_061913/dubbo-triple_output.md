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
# Warmup Iteration   1: 1.483 ops/ms
# Warmup Iteration   2: 3.637 ops/ms
# Warmup Iteration   3: 7.202 ops/ms
Iteration   1: 7.672 ops/ms
Iteration   2: 8.175 ops/ms
Iteration   3: 8.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.988 ±(99.9%) 5.014 ops/ms [Average]
  (min, avg, max) = (7.672, 7.988, 8.175), stdev = 0.275
  CI (99.9%): [2.973, 13.002] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.189 ops/ms
# Warmup Iteration   2: 6.804 ops/ms
# Warmup Iteration   3: 8.048 ops/ms
Iteration   1: 8.434 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.291 ±(99.9%) 3.172 ops/ms [Average]
  (min, avg, max) = (8.098, 8.291, 8.434), stdev = 0.174
  CI (99.9%): [5.119, 11.463] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.216 ops/ms
# Warmup Iteration   2: 6.156 ops/ms
# Warmup Iteration   3: 7.959 ops/ms
Iteration   1: 7.643 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 7.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.868 ±(99.9%) 6.424 ops/ms [Average]
  (min, avg, max) = (7.643, 7.868, 8.274), stdev = 0.352
  CI (99.9%): [1.444, 14.293] (assumes normal distribution)


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
# Warmup Iteration   1: 1.952 ops/ms
# Warmup Iteration   2: 5.576 ops/ms
# Warmup Iteration   3: 6.593 ops/ms
Iteration   1: 6.721 ops/ms
Iteration   2: 6.683 ops/ms
Iteration   3: 6.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.725 ±(99.9%) 0.809 ops/ms [Average]
  (min, avg, max) = (6.683, 6.725, 6.771), stdev = 0.044
  CI (99.9%): [5.916, 7.535] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.160 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.495 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.015 ms/op
Iteration   1: 4.176 ±(99.9%) 0.004 ms/op
Iteration   2: 3.929 ±(99.9%) 0.006 ms/op
Iteration   3: 4.095 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.067 ±(99.9%) 2.297 ms/op [Average]
  (min, avg, max) = (3.929, 4.067, 4.176), stdev = 0.126
  CI (99.9%): [1.770, 6.364] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.224 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.008 ms/op
Iteration   1: 3.854 ±(99.9%) 0.009 ms/op
Iteration   2: 3.865 ±(99.9%) 0.004 ms/op
Iteration   3: 3.912 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.877 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (3.854, 3.877, 3.912), stdev = 0.031
  CI (99.9%): [3.312, 4.443] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.809 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.865 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.004 ms/op
Iteration   1: 4.009 ±(99.9%) 0.009 ms/op
Iteration   2: 3.955 ±(99.9%) 0.005 ms/op
Iteration   3: 4.009 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.991 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.955, 3.991, 4.009), stdev = 0.031
  CI (99.9%): [3.422, 4.559] (assumes normal distribution)


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
# Warmup Iteration   1: 16.157 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.619 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.809 ±(99.9%) 0.013 ms/op
Iteration   1: 4.548 ±(99.9%) 0.019 ms/op
Iteration   2: 4.631 ±(99.9%) 0.014 ms/op
Iteration   3: 4.594 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.591 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (4.548, 4.591, 4.631), stdev = 0.042
  CI (99.9%): [3.834, 5.349] (assumes normal distribution)


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
# Warmup Iteration   1: 14.367 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 4.893 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.021 ms/op
Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  23.757 ms/op
                 createUser·p0.9999: 26.042 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.886 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  22.184 ms/op
                 createUser·p0.9999: 34.602 ms/op
                 createUser·p1.00:   34.800 ms/op

Iteration   3: 4.008 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  28.421 ms/op
                 createUser·p0.9999: 33.489 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242436
  mean =      3.957 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 263 
    [ 2.500,  5.000) = 229994 
    [ 5.000,  7.500) = 10657 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 38 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.067 ms/op
     p(99.9000) =     24.037 ms/op
     p(99.9900) =     33.350 ms/op
     p(99.9990) =     34.772 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 12.768 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.551 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.012 ms/op
Iteration   1: 3.871 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.050 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.809 ms/op
                 existUser·p0.999:  10.267 ms/op
                 existUser·p0.9999: 25.649 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 3.939 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  24.510 ms/op
                 existUser·p0.9999: 26.800 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.075 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  19.644 ms/op
                 existUser·p0.9999: 30.671 ms/op
                 existUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247428
  mean =      3.879 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 163 
    [ 2.500,  5.000) = 237272 
    [ 5.000,  7.500) = 8484 
    [ 7.500, 10.000) = 926 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.679 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     19.207 ms/op
     p(99.9900) =     29.156 ms/op
     p(99.9990) =     30.836 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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
# Warmup Iteration   1: 12.856 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.015 ms/op
Iteration   1: 3.944 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  24.008 ms/op
                 getUser·p0.9999: 26.984 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   2: 4.049 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.048 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  13.255 ms/op
                 getUser·p0.9999: 27.302 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   3: 4.008 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   8.028 ms/op
                 getUser·p0.999:  26.125 ms/op
                 getUser·p0.9999: 32.736 ms/op
                 getUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239815
  mean =      4.000 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 229518 
    [ 5.000,  7.500) = 7818 
    [ 7.500, 10.000) = 1609 
    [10.000, 12.500) = 409 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 139 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     23.754 ms/op
     p(99.9900) =     31.523 ms/op
     p(99.9990) =     33.477 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 15.528 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 6.019 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 4.978 ±(99.9%) 0.020 ms/op
Iteration   1: 4.866 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   10.470 ms/op
                 listUser·p0.999:  26.083 ms/op
                 listUser·p0.9999: 29.290 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   2: 4.692 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  17.948 ms/op
                 listUser·p0.9999: 24.127 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   3: 4.726 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  17.572 ms/op
                 listUser·p0.9999: 21.019 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201573
  mean =      4.760 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 170052 
    [ 5.000,  7.500) = 26339 
    [ 7.500, 10.000) = 3882 
    [10.000, 12.500) = 627 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.212 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     27.613 ms/op
     p(99.9990) =     30.701 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.988 ± 5.014  ops/ms
ClientPb.existUser                       thrpt       3   8.291 ± 3.172  ops/ms
ClientPb.getUser                         thrpt       3   7.868 ± 6.424  ops/ms
ClientPb.listUser                        thrpt       3   6.725 ± 0.809  ops/ms
ClientPb.createUser                       avgt       3   4.067 ± 2.297   ms/op
ClientPb.existUser                        avgt       3   3.877 ± 0.566   ms/op
ClientPb.getUser                          avgt       3   3.991 ± 0.568   ms/op
ClientPb.listUser                         avgt       3   4.591 ± 0.758   ms/op
ClientPb.createUser                     sample  242436   3.957 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.067           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.037           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.350           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  247428   3.879 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.679           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.586           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.207           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.156           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.326           ms/op
ClientPb.getUser                        sample  239815   4.000 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.571           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.754           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.523           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.013           ms/op
ClientPb.listUser                       sample  201573   4.760 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.212           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.060           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.840           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.613           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.850           ms/op
