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
# Warmup Iteration   1: 1.418 ops/ms
# Warmup Iteration   2: 3.580 ops/ms
# Warmup Iteration   3: 5.704 ops/ms
Iteration   1: 5.797 ops/ms
Iteration   2: 6.217 ops/ms
Iteration   3: 6.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.165 ±(99.9%) 6.299 ops/ms [Average]
  (min, avg, max) = (5.797, 6.165, 6.482), stdev = 0.345
  CI (99.9%): [≈ 0, 12.464] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.117 ops/ms
# Warmup Iteration   2: 5.853 ops/ms
# Warmup Iteration   3: 6.007 ops/ms
Iteration   1: 6.386 ops/ms
Iteration   2: 6.820 ops/ms
Iteration   3: 6.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.706 ±(99.9%) 5.113 ops/ms [Average]
  (min, avg, max) = (6.386, 6.706, 6.911), stdev = 0.280
  CI (99.9%): [1.593, 11.818] (assumes normal distribution)


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
# Warmup Iteration   1: 2.009 ops/ms
# Warmup Iteration   2: 5.133 ops/ms
# Warmup Iteration   3: 6.107 ops/ms
Iteration   1: 6.226 ops/ms
Iteration   2: 6.883 ops/ms
Iteration   3: 6.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.553 ±(99.9%) 5.994 ops/ms [Average]
  (min, avg, max) = (6.226, 6.553, 6.883), stdev = 0.329
  CI (99.9%): [0.560, 12.547] (assumes normal distribution)


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
# Warmup Iteration   1: 1.478 ops/ms
# Warmup Iteration   2: 3.822 ops/ms
# Warmup Iteration   3: 4.759 ops/ms
Iteration   1: 5.313 ops/ms
Iteration   2: 5.310 ops/ms
Iteration   3: 5.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.369 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (5.310, 5.369, 5.486), stdev = 0.101
  CI (99.9%): [3.527, 7.212] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.573 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.454 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.141 ±(99.9%) 0.008 ms/op
Iteration   1: 4.847 ±(99.9%) 0.016 ms/op
Iteration   2: 4.866 ±(99.9%) 0.010 ms/op
Iteration   3: 5.298 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.003 ±(99.9%) 4.656 ms/op [Average]
  (min, avg, max) = (4.847, 5.003, 5.298), stdev = 0.255
  CI (99.9%): [0.347, 9.660] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.255 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.628 ±(99.9%) 0.007 ms/op
Iteration   1: 4.629 ±(99.9%) 0.007 ms/op
Iteration   2: 4.794 ±(99.9%) 0.015 ms/op
Iteration   3: 5.030 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.818 ±(99.9%) 3.684 ms/op [Average]
  (min, avg, max) = (4.629, 4.818, 5.030), stdev = 0.202
  CI (99.9%): [1.133, 8.502] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.497 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.907 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.125 ±(99.9%) 0.012 ms/op
Iteration   1: 4.989 ±(99.9%) 0.010 ms/op
Iteration   2: 5.493 ±(99.9%) 0.008 ms/op
Iteration   3: 5.413 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.298 ±(99.9%) 4.941 ms/op [Average]
  (min, avg, max) = (4.989, 5.298, 5.493), stdev = 0.271
  CI (99.9%): [0.357, 10.240] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.547 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.835 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.833 ±(99.9%) 0.013 ms/op
Iteration   1: 6.089 ±(99.9%) 0.010 ms/op
Iteration   2: 6.080 ±(99.9%) 0.013 ms/op
Iteration   3: 6.179 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.116 ±(99.9%) 1.005 ms/op [Average]
  (min, avg, max) = (6.080, 6.116, 6.179), stdev = 0.055
  CI (99.9%): [5.111, 7.121] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.214 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.979 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.488 ±(99.9%) 0.024 ms/op
Iteration   1: 5.505 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.384 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   8.053 ms/op
                 createUser·p0.99:   10.486 ms/op
                 createUser·p0.999:  24.183 ms/op
                 createUser·p0.9999: 28.094 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   2: 5.446 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.651 ms/op
                 createUser·p0.99:   10.475 ms/op
                 createUser·p0.999:  26.189 ms/op
                 createUser·p0.9999: 31.875 ms/op
                 createUser·p1.00:   32.244 ms/op

Iteration   3: 5.200 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.250 ms/op
                 createUser·p0.99:   9.650 ms/op
                 createUser·p0.999:  24.478 ms/op
                 createUser·p0.9999: 32.416 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178353
  mean =      5.380 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 82405 
    [ 5.000,  7.500) = 86177 
    [ 7.500, 10.000) = 7782 
    [10.000, 12.500) = 1178 
    [12.500, 15.000) = 356 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     24.695 ms/op
     p(99.9900) =     31.752 ms/op
     p(99.9990) =     33.051 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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
# Warmup Iteration   1: 13.308 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 4.970 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.353 ±(99.9%) 0.019 ms/op
Iteration   1: 5.386 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   7.537 ms/op
                 existUser·p0.99:   10.502 ms/op
                 existUser·p0.999:  16.302 ms/op
                 existUser·p0.9999: 27.433 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 4.914 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   7.012 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  15.902 ms/op
                 existUser·p0.9999: 35.717 ms/op
                 existUser·p1.00:   37.945 ms/op

Iteration   3: 4.776 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   4.506 ms/op
                 existUser·p0.90:   5.964 ms/op
                 existUser·p0.95:   6.709 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  15.856 ms/op
                 existUser·p0.9999: 32.539 ms/op
                 existUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 191446
  mean =      5.012 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 114386 
    [ 5.000,  7.500) = 69642 
    [ 7.500, 10.000) = 5427 
    [10.000, 12.500) = 1314 
    [12.500, 15.000) = 360 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.094 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     16.212 ms/op
     p(99.9900) =     34.565 ms/op
     p(99.9990) =     37.885 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 14.860 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.764 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.742 ±(99.9%) 0.024 ms/op
Iteration   1: 5.173 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.960 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   6.291 ms/op
                 getUser·p0.95:   7.201 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  21.149 ms/op
                 getUser·p0.9999: 25.266 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 5.507 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.224 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   8.028 ms/op
                 getUser·p0.99:   12.124 ms/op
                 getUser·p0.999:  25.063 ms/op
                 getUser·p0.9999: 30.316 ms/op
                 getUser·p1.00:   33.423 ms/op

Iteration   3: 5.118 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.433 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   6.423 ms/op
                 getUser·p0.95:   7.283 ms/op
                 getUser·p0.99:   9.912 ms/op
                 getUser·p0.999:  25.199 ms/op
                 getUser·p0.9999: 29.213 ms/op
                 getUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182363
  mean =      5.261 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 88481 
    [ 5.000,  7.500) = 84603 
    [ 7.500, 10.000) = 6562 
    [10.000, 12.500) = 1744 
    [12.500, 15.000) = 538 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.960 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.528 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     29.354 ms/op
     p(99.9990) =     33.423 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.551 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 7.371 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.354 ±(99.9%) 0.027 ms/op
Iteration   1: 6.213 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  27.835 ms/op
                 listUser·p0.9999: 39.170 ms/op
                 listUser·p1.00:   40.698 ms/op

Iteration   2: 6.142 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.525 ms/op
                 listUser·p0.999:  28.410 ms/op
                 listUser·p0.9999: 31.556 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   3: 5.684 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.036 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  18.932 ms/op
                 listUser·p0.9999: 23.585 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159828
  mean =      6.004 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 26320 
    [ 5.000, 10.000) = 130382 
    [10.000, 15.000) = 2647 
    [15.000, 20.000) = 202 
    [20.000, 25.000) = 90 
    [25.000, 30.000) = 134 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.339 ms/op
     p(50.0000) =      5.644 ms/op
     p(90.0000) =      7.496 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.452 ms/op
     p(99.9000) =     26.449 ms/op
     p(99.9900) =     36.047 ms/op
     p(99.9990) =     40.188 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.165 ± 6.299  ops/ms
ClientPb.existUser                       thrpt       3   6.706 ± 5.113  ops/ms
ClientPb.getUser                         thrpt       3   6.553 ± 5.994  ops/ms
ClientPb.listUser                        thrpt       3   5.369 ± 1.842  ops/ms
ClientPb.createUser                       avgt       3   5.003 ± 4.656   ms/op
ClientPb.existUser                        avgt       3   4.818 ± 3.684   ms/op
ClientPb.getUser                          avgt       3   5.298 ± 4.941   ms/op
ClientPb.listUser                         avgt       3   6.116 ± 1.005   ms/op
ClientPb.createUser                     sample  178353   5.380 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.791           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.079           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.709           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.627           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.158           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.695           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.752           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.128           ms/op
ClientPb.existUser                      sample  191446   5.012 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.047           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.743           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.094           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.027           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.212           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.565           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.945           ms/op
ClientPb.getUser                        sample  182363   5.261 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.960           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.977           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.839           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.354           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.423           ms/op
ClientPb.listUser                       sample  159828   6.004 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.339           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.452           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.449           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.047           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.698           ms/op
