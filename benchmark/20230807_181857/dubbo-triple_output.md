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
# Warmup Iteration   1: 2.488 ops/ms
# Warmup Iteration   2: 6.136 ops/ms
# Warmup Iteration   3: 8.995 ops/ms
Iteration   1: 9.700 ops/ms
Iteration   2: 10.094 ops/ms
Iteration   3: 9.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.907 ±(99.9%) 3.611 ops/ms [Average]
  (min, avg, max) = (9.700, 9.907, 10.094), stdev = 0.198
  CI (99.9%): [6.296, 13.519] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.608 ops/ms
# Warmup Iteration   2: 9.371 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 10.108 ops/ms
Iteration   2: 10.181 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.246 ±(99.9%) 3.285 ops/ms [Average]
  (min, avg, max) = (10.108, 10.246, 10.450), stdev = 0.180
  CI (99.9%): [6.961, 13.531] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.361 ops/ms
# Warmup Iteration   2: 8.867 ops/ms
# Warmup Iteration   3: 9.392 ops/ms
Iteration   1: 9.775 ops/ms
Iteration   2: 10.034 ops/ms
Iteration   3: 10.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.947 ±(99.9%) 2.721 ops/ms [Average]
  (min, avg, max) = (9.775, 9.947, 10.034), stdev = 0.149
  CI (99.9%): [7.226, 12.668] (assumes normal distribution)


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
# Warmup Iteration   1: 3.000 ops/ms
# Warmup Iteration   2: 7.626 ops/ms
# Warmup Iteration   3: 8.206 ops/ms
Iteration   1: 8.430 ops/ms
Iteration   2: 8.539 ops/ms
Iteration   3: 8.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.405 ±(99.9%) 2.723 ops/ms [Average]
  (min, avg, max) = (8.244, 8.405, 8.539), stdev = 0.149
  CI (99.9%): [5.681, 11.128] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.888 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.003 ms/op
Iteration   1: 3.378 ±(99.9%) 0.006 ms/op
Iteration   2: 3.293 ±(99.9%) 0.003 ms/op
Iteration   3: 3.325 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.332 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (3.293, 3.332, 3.378), stdev = 0.043
  CI (99.9%): [2.548, 4.117] (assumes normal distribution)


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
# Warmup Iteration   1: 6.892 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.005 ms/op
Iteration   1: 3.183 ±(99.9%) 0.002 ms/op
Iteration   2: 3.214 ±(99.9%) 0.002 ms/op
Iteration   3: 3.040 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.146 ±(99.9%) 1.695 ms/op [Average]
  (min, avg, max) = (3.040, 3.146, 3.214), stdev = 0.093
  CI (99.9%): [1.450, 4.841] (assumes normal distribution)


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
# Warmup Iteration   1: 7.299 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.005 ms/op
Iteration   1: 3.261 ±(99.9%) 0.003 ms/op
Iteration   2: 3.211 ±(99.9%) 0.006 ms/op
Iteration   3: 3.225 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.232 ±(99.9%) 0.466 ms/op [Average]
  (min, avg, max) = (3.211, 3.232, 3.261), stdev = 0.026
  CI (99.9%): [2.766, 3.698] (assumes normal distribution)


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
# Warmup Iteration   1: 9.057 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.005 ms/op
Iteration   1: 3.609 ±(99.9%) 0.012 ms/op
Iteration   2: 3.720 ±(99.9%) 0.009 ms/op
Iteration   3: 3.749 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.693 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (3.609, 3.693, 3.749), stdev = 0.074
  CI (99.9%): [2.352, 5.034] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.957 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.010 ms/op
Iteration   1: 3.218 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  15.181 ms/op
                 createUser·p0.9999: 20.220 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 3.248 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.686 ms/op
                 createUser·p0.999:  10.417 ms/op
                 createUser·p0.9999: 23.571 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.210 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  17.806 ms/op
                 createUser·p0.9999: 35.523 ms/op
                 createUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297447
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17151 
    [ 2.500,  5.000) = 274304 
    [ 5.000,  7.500) = 4447 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     36.389 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 7.555 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.008 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 18.297 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  15.502 ms/op
                 existUser·p0.9999: 20.185 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   3: 3.266 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.229 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 22.788 ms/op
                 existUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300020
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23483 
    [ 2.500,  5.000) = 269436 
    [ 5.000,  7.500) = 5862 
    [ 7.500, 10.000) = 869 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.229 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     23.789 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 7.332 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.010 ms/op
Iteration   1: 3.230 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  12.190 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 27.322 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.150 ms/op
                 getUser·p0.999:  13.836 ms/op
                 getUser·p0.9999: 23.036 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293806
  mean =      3.266 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13881 
    [ 2.500,  5.000) = 270723 
    [ 5.000,  7.500) = 7971 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     12.137 ms/op
     p(99.9900) =     26.328 ms/op
     p(99.9990) =     28.690 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 9.567 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.012 ms/op
Iteration   1: 3.872 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  20.513 ms/op
                 listUser·p0.9999: 23.108 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 3.832 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   3: 3.854 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249095
  mean =      3.852 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 237632 
    [ 5.000,  7.500) = 8289 
    [ 7.500, 10.000) = 2310 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 319 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     22.556 ms/op
     p(99.9990) =     23.840 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.907 ± 3.611  ops/ms
ClientPb.existUser                       thrpt       3  10.246 ± 3.285  ops/ms
ClientPb.getUser                         thrpt       3   9.947 ± 2.721  ops/ms
ClientPb.listUser                        thrpt       3   8.405 ± 2.723  ops/ms
ClientPb.createUser                       avgt       3   3.332 ± 0.784   ms/op
ClientPb.existUser                        avgt       3   3.146 ± 1.695   ms/op
ClientPb.getUser                          avgt       3   3.232 ± 0.466   ms/op
ClientPb.listUser                         avgt       3   3.693 ± 1.341   ms/op
ClientPb.createUser                     sample  297447   3.225 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.034           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.980           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.498           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.406           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.159           ms/op
ClientPb.existUser                      sample  300020   3.196 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.229           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.910           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.644           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.379           ms/op
ClientPb.getUser                        sample  293806   3.266 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.926           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.210           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.137           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.328           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.065           ms/op
ClientPb.listUser                       sample  249095   3.852 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.499           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.074           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.556           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.986           ms/op
