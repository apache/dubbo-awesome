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
# Warmup Iteration   1: 2.719 ops/ms
# Warmup Iteration   2: 6.140 ops/ms
# Warmup Iteration   3: 8.767 ops/ms
Iteration   1: 9.472 ops/ms
Iteration   2: 9.548 ops/ms
Iteration   3: 9.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.604 ±(99.9%) 3.054 ops/ms [Average]
  (min, avg, max) = (9.472, 9.604, 9.793), stdev = 0.167
  CI (99.9%): [6.550, 12.658] (assumes normal distribution)


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
# Warmup Iteration   1: 3.507 ops/ms
# Warmup Iteration   2: 9.091 ops/ms
# Warmup Iteration   3: 9.611 ops/ms
Iteration   1: 9.745 ops/ms
Iteration   2: 9.724 ops/ms
Iteration   3: 10.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.851 ±(99.9%) 3.662 ops/ms [Average]
  (min, avg, max) = (9.724, 9.851, 10.082), stdev = 0.201
  CI (99.9%): [6.189, 13.512] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.850 ops/ms
# Warmup Iteration   2: 7.990 ops/ms
# Warmup Iteration   3: 9.229 ops/ms
Iteration   1: 9.060 ops/ms
Iteration   2: 9.228 ops/ms
Iteration   3: 9.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.104 ±(99.9%) 1.972 ops/ms [Average]
  (min, avg, max) = (9.026, 9.104, 9.228), stdev = 0.108
  CI (99.9%): [7.132, 11.076] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.585 ops/ms
# Warmup Iteration   2: 7.366 ops/ms
# Warmup Iteration   3: 7.956 ops/ms
Iteration   1: 7.850 ops/ms
Iteration   2: 8.089 ops/ms
Iteration   3: 7.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.956 ±(99.9%) 2.215 ops/ms [Average]
  (min, avg, max) = (7.850, 7.956, 8.089), stdev = 0.121
  CI (99.9%): [5.740, 10.171] (assumes normal distribution)


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
# Warmup Iteration   1: 9.052 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.005 ms/op
Iteration   1: 3.513 ±(99.9%) 0.008 ms/op
Iteration   2: 3.350 ±(99.9%) 0.004 ms/op
Iteration   3: 3.328 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.397 ±(99.9%) 1.840 ms/op [Average]
  (min, avg, max) = (3.328, 3.397, 3.513), stdev = 0.101
  CI (99.9%): [1.556, 5.237] (assumes normal distribution)


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
# Warmup Iteration   1: 9.109 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.005 ms/op
Iteration   1: 3.273 ±(99.9%) 0.008 ms/op
Iteration   2: 3.382 ±(99.9%) 0.007 ms/op
Iteration   3: 3.267 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.308 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (3.267, 3.308, 3.382), stdev = 0.065
  CI (99.9%): [2.124, 4.491] (assumes normal distribution)


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
# Warmup Iteration   1: 8.605 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.006 ms/op
Iteration   1: 3.532 ±(99.9%) 0.004 ms/op
Iteration   2: 3.368 ±(99.9%) 0.008 ms/op
Iteration   3: 3.375 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.425 ±(99.9%) 1.684 ms/op [Average]
  (min, avg, max) = (3.368, 3.425, 3.532), stdev = 0.092
  CI (99.9%): [1.741, 5.109] (assumes normal distribution)


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
# Warmup Iteration   1: 9.874 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.940 ±(99.9%) 0.007 ms/op
Iteration   2: 3.871 ±(99.9%) 0.009 ms/op
Iteration   3: 3.870 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.893 ±(99.9%) 0.732 ms/op [Average]
  (min, avg, max) = (3.870, 3.893, 3.940), stdev = 0.040
  CI (99.9%): [3.162, 4.625] (assumes normal distribution)


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
# Warmup Iteration   1: 9.710 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.010 ms/op
Iteration   1: 3.330 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  17.598 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.373 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  19.968 ms/op
                 createUser·p0.9999: 25.250 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.398 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.367 ms/op
                 createUser·p0.999:  15.416 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284973
  mean =      3.367 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11725 
    [ 2.500,  5.000) = 266294 
    [ 5.000,  7.500) = 5370 
    [ 7.500, 10.000) = 1047 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     24.839 ms/op
     p(99.9990) =     26.383 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 7.932 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
Iteration   1: 3.356 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  18.452 ms/op
                 existUser·p0.9999: 21.249 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 3.449 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  14.336 ms/op
                 existUser·p0.9999: 24.942 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.422 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  18.585 ms/op
                 existUser·p0.9999: 26.431 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281487
  mean =      3.409 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10018 
    [ 2.500,  5.000) = 261699 
    [ 5.000,  7.500) = 7717 
    [ 7.500, 10.000) = 1604 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     27.400 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 9.376 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.011 ms/op
Iteration   1: 3.492 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  17.001 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   2: 3.471 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.970 ms/op
                 getUser·p0.999:  20.055 ms/op
                 getUser·p0.9999: 25.650 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.403 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  16.843 ms/op
                 getUser·p0.9999: 26.890 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277651
  mean =      3.455 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15749 
    [ 2.500,  5.000) = 250948 
    [ 5.000,  7.500) = 8907 
    [ 7.500, 10.000) = 1545 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     25.698 ms/op
     p(99.9990) =     27.875 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 10.570 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.013 ms/op
Iteration   1: 3.957 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.453 ms/op
                 listUser·p0.999:  15.699 ms/op
                 listUser·p0.9999: 20.015 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.934 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 16.586 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 3.874 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.920 ms/op
                 listUser·p0.999:  14.327 ms/op
                 listUser·p0.9999: 18.637 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244790
  mean =      3.922 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 234310 
    [ 5.000,  7.500) = 6930 
    [ 7.500, 10.000) = 2495 
    [10.000, 12.500) = 473 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     14.896 ms/op
     p(99.9900) =     19.088 ms/op
     p(99.9990) =     20.902 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.604 ± 3.054  ops/ms
ClientPb.existUser                       thrpt       3   9.851 ± 3.662  ops/ms
ClientPb.getUser                         thrpt       3   9.104 ± 1.972  ops/ms
ClientPb.listUser                        thrpt       3   7.956 ± 2.215  ops/ms
ClientPb.createUser                       avgt       3   3.397 ± 1.840   ms/op
ClientPb.existUser                        avgt       3   3.308 ± 1.184   ms/op
ClientPb.getUser                          avgt       3   3.425 ± 1.684   ms/op
ClientPb.listUser                         avgt       3   3.893 ± 0.732   ms/op
ClientPb.createUser                     sample  284973   3.367 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.128           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.300           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.892           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.839           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.575           ms/op
ClientPb.existUser                      sample  281487   3.409 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.098           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.369           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.133           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  277651   3.455 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.182           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.974           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.698           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.377           ms/op
ClientPb.listUser                       sample  244790   3.922 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.704           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.126           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.896           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.088           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.332           ms/op
